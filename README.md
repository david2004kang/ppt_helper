|版本|更新日期|修改履歷|作者|
|---|---|---|---|
|0.01|2020/04/09|在github上建立了新的Project|David Kang|

****

## 緣起
    因為教會需要投影，包含敬拜及講道時隨時要找到相關經文投影。
    或是有時要用VLC放一些影片，及用youtube-dl 下載一些MP3，影片等等…
    所以我剛好練習用wxPython寫一個有GUI的應用程式。
    另外因為教會是用MAC的，所以還包含了py2app的setup.py等等。

****

## 程式功能

    1. 使用python-pptx來放投影片
    2. 使用open -n /Applications/Microsoft\ PowerPoint.app/ 來開一個新的Power pointe Instance
    3. 有GUI及設定讓python-pptx來放特定經文投影片，及設定目前經文投影片的路徑。
    4. 呼叫youtube-dl 來下載youtube的影片及MP3

****

## 完成進度
    - [ ] GUI基本完成
    - [ ] 可以用youtube-dl下載影片及MP3
    - [ ] 可以用設定檔，可以開經文投影片
    
    其他的項目會陸續加上。
