## 交作業流程
1. 先在 Lidemy 的第四期課程 GitHub 開一個 fork 到自己的 GitHub 的 Repository 或下載到自己的電腦
2.在此資料夾下打開 terminal 輸入`git init`，然後 **再開一個 branch** 輸入 `git branch <當週作業名稱>`
3. 打開資料夾內的 **homeworks** 資料夾
4. 選擇當週作業撰寫 
5. 寫完後，確定自己所在位置是 **branch**（若不在 branch，可以在 terminal 輸入 `git checkout  <要切換的branch名稱>`），將所有修改過的檔案加入版本控制。打開 **terminal** `Mac os才有，Windows系統叫命令提示字元`輸入 `git add .`，之後再輸入 `git commit -m <版本敘述>`
6. 將本地端修改後的檔案推送至遠端（GitHub）。於 terminal 輸入`git push -u origin master ` 
7. 確定推送到遠端後，打開 GitHub 的 **Pull request**，點選 **compare & pull request**，將上傳的檔案 merge 到遠端的 master
8. 若沒有出現 **compare & pull request**，可以選擇 **Creat pull request**，然後選擇上傳 branch 的名稱
9.等待更改完後，在本地端（**確認自己要在 master 上，而不是 branch上**），打開 terminal 輸入`git pull origin master`。**讓遠端的 master 和本地端的 master 同步**（**在做此步驟前，確定本地端沒有任何檔案要 commit**）
10. 之後刪除本地端的 branch `git branch -d <要刪除的branch名稱>`
