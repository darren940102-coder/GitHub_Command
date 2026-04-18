Github 版本控制

影片教學:https://www.youtube.com/watch?v=FKXRiAiQFiY&t=664s

1.查看版本: 
    git --version

2.設定使用者:

    User: git config --global user.name "user"     #在 "user" 中填入使用者名稱

    email: git config --global user.email "email"  #在 "email" 中填入信箱

3.初始化:
    git init

4.清除終端機畫面:

    在終端機輸入    clear 
        or 
    鍵盤直接輸入    ctrl + L  

5.檢查檔案狀態:
    git status

6.追蹤檔案:
    git add filename    # filename 是要追蹤的檔案名稱
    git add *.md        # 追蹤所有副檔名為.md的檔案 
    git add .           # 追蹤當前目錄所有檔案

7.檔案型態:
    filename U    # 檔案為追蹤
    filename A    # 檔案以追蹤
    filename M    # 檔案已有存檔但有更動過

8.提交(存檔):
    git commit -m "建立還原點"

9.儲存:
    ctrl + s

10.檢視:
    git log
    git log --oneline

11.比較差異:
    git diff 檔案ID

12.還原檔案:
    git checkout 要還原到的檔案ID --filename

13.上傳到github:

連結本地和遠端的儲存庫
git remote add origin https://github.com/darren940102-coder/GitHub_Command.git

修改詞語 Master => main
git branch -M main

把本地位於main的資料推送到雲端
git push -u origin main