# jeff-test-one     [For RedHat OpenShift.io - Sandbox]

這是我的測試區，用來測試專案建立、寫程式等相關練習。

## Java 練習

1. HelloWorld.java

## Lombok Project 範例說明

Lombok 是一個開源的 Java 程式庫，透過註解減少重複性的程式碼。

本專案包含使用與未使用 Lombok 的 POJO 範例，以及示範 Lombok 行為的測試方法。

Lombok 官方文件：https://projectlombok.org/

原始範例的西班牙文教學：https://codesolt.com/tutoriales/

原始範例作者：https://carlos-salazar.com/

------------------------------------------------------------
2026 10/13 21:26
今晚你學會了什麼？
Git 衝突處理：解決兩邊都有 README.md 的衝突。

Git 合併提交：把本機與 GitHub 原本不同的提交歷史接合起來。

GitHub 裝置驗證：完成 VS Code - Open Source 的 GitHub 登入授權。

Git 推送：成功將本機 master 推送至 GitHub 的 main。

將 README.md 標記為已解決

> git add README.md

完成合併提交
如果 git status 顯示衝突已解決，而且沒有其他未解決的衝突，就輸入：

> git commit -m "中文字也可以唷，Merge GitHub README with Lombok project"

這會建立一筆合併提交，將本機 master 與 GitHub main 的歷史接合起來。

先確認分支與遠端設定
完成提交後，請輸入：

> git status

再輸入

> git remote -v

推送到 GitHub
因為你目前的本機分支叫 master，而 GitHub 的分支叫 main，我們可以明確指定把本機 master 推送到遠端 main。

> git push origin master:main

------------------
這個指令的意思是：
- origin：你的 GitHub 儲存庫。
- master：OpenShift 本機分支。
- main：GitHub 遠端分支。
------------------
它可以明確指定把本機 master 分支推送到 GitHub 的 main 分支。
不過，因為目前兩邊分支名稱不同，往後我們可以再整理成一致的分支管理方式，讓你練習 Java 時更方便。
你先做最後一次同步確認。 確認完成後，我們就可以接著練習如何在 OpenShift 修改 Java 程式、提交變更，再同步到 GitHub。

1.推送完成後，確認是否同步
如果上一步顯示推送成功，請再輸入：

> git fetch origin

接著輸入：

> git status

最後輸入：

> git log -3 --oneline --graph --decorate



