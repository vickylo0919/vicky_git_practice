# vicky_git_practice

Git 上傳
1.開啟cmd 先指定到想要存的地方 (ex: 想存在D槽，先指定到D槽 輸入cd /d D:)
2.創一個資料夾在D槽 (ex: 創一個叫github的資料夾)
3.輸入git clone github資料庫的網址 (ex: git clone https://github.com/yiyun12o9/yiyun_practice)
4.找到複製下來的資料夾，將要上傳的unity專案拉進去
5.將複製下來的資料夾裡面的[.gitignore]複製到每個unity專案裡
6.開啟cmd 指定到複製下來資料夾裡 (ex: cd D:\github\yiyun_practice)
7.輸入git status 看到紅色字為未上傳的檔案
8.輸入git add . (是add空格.)
9.輸入git commit -m "隨便打"
10輸入git push (有時會遇到不同步的問題，先試試git pull再git push)
