## 交作業流程
1. 先在Lidemy 的第四期課程GitHub開一個fork到自己的GitHub的Repository或下載到自己的電腦
2.在此資料夾下打開terminal輸入`git init`，然後**再開一個branch**輸入`git branch <當週作業名稱>`
3. 打開資料夾內的**homeworks**資料夾
4. 選擇當週作業撰寫
5. 寫完後，確定自己所在位置是**branch**（若不在branch，可以在terminal輸入`git checkout <要切換的branch名稱>`），將所有修改過的檔案加入版本控制。打開**terminal**`Mac os才有，Windows系統叫命令提示字元`輸入`git add .`，之後再輸入`git commit -m <版本敘述>`
6. 將本地端修改後的檔案推送至遠端（GitHub）。於terminal輸入`git push -u origin master ` 
7. 確定推送到遠端後，打開GitHub的**Pull request**，點選**compare & pull request**，將上傳的檔案merge到遠端的master
8. 若沒有出現**compare & pull request**，可以選擇**Creat pull request**，然後選擇上傳branch的名稱
9.等待更改完後，在本地端（**確認自己要在master上，而不是branch上**），打開terminal輸入`git pull origin master`。**讓遠端的master和本地端的master同步**（**在做此步驟前，確定本地端沒有任何檔案要commit**）
10. 之後刪除本地端的branch`git branch -d <要刪除的branch名稱>`
