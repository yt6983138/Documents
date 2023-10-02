# Chinese
## Android
### Root過的裝置
```shell
cmd> adb shell
sh> su
sh# cp /data/data/com.PigeonGames.Phigros/shared_prefs/com.PigeonGames.Phigros.v2.playerprefs.xml /storage/emulated/0/
sh# exit
sh> exit
cmd> adb pull /storage/emulated/0/com.PigeonGames.Phigros.v2.playerprefs.xml
```
然後去 [rks查詢工具](https://lchzh3473.github.io/rks-probe/) 上傳存檔 (com.PigeonGames.Phigros.v2.playerprefs.xml)
ex. ![image](https://github.com/yt6983138/Documents/assets/83499886/32c57305-54b0-470c-ab4a-5e3db08e48f6)
### 沒root
兩種方法:
1. [Google Sheet 查詢](https://docs.google.com/spreadsheets/d/1_FpXuHJ5NU-nuu2TMw6c6RwMla4NdoSxIWe5cncyquo/edit)
2. 用adb, 詳情如下
```shell
cmd> adb backup com.PigeonGames.Phigros backup.ab
或
cmd> adb backup com.PigeonGames.PhigrosGlobal backup.ab
```
然後去 [rks查詢工具](https://lchzh3473.github.io/rks-probe/) 上傳存檔 (backup.ab)
## iOS
沒救 去 [Google Sheet 查詢](https://docs.google.com/spreadsheets/d/1_FpXuHJ5NU-nuu2TMw6c6RwMla4NdoSxIWe5cncyquo/edit)
# English
## Android
### Rooted Device
```shell
cmd> adb shell
sh> su
sh# cp /data/data/com.PigeonGames.Phigros/shared_prefs/com.PigeonGames.Phigros.v2.playerprefs.xml /storage/emulated/0/
Note: If com.PigeonGames.Phigros doesn't work try com.PigeonGames.PhigrosGlobal instead
sh# exit
sh> exit
cmd> adb pull /storage/emulated/0/com.PigeonGames.Phigros.v2.playerprefs.xml
```
Then go to [rks lookup](https://lchzh3473.github.io/rks-probe/) and upload your save (com.PigeonGames.Phigros.v2.playerprefs.xml)
### Unrooted Device
Two ways:
1. [Google Sheet look up](https://docs.google.com/spreadsheets/d/1_FpXuHJ5NU-nuu2TMw6c6RwMla4NdoSxIWe5cncyquo/edit)
2. Use `adb backup` command, command below
```shell
cmd> adb backup com.PigeonGames.Phigros backup.ab
or
cmd> adb backup com.PigeonGames.PhigrosGlobal backup.ab
```
Then go to [rks lookup](https://lchzh3473.github.io/rks-probe/) and upload your save (backup.ab)
## iOS
i dont use apple shits so go to [Google Sheet look up](https://docs.google.com/spreadsheets/d/1_FpXuHJ5NU-nuu2TMw6c6RwMla4NdoSxIWe5cncyquo/edit)
