# Ch1 : Git Version control

  
通識課程 - Git

## **Github - \(6/29/2018\)** {#github-6-29-2018}

**1. Github 註冊流程**

**2. Fork other Github resource**

**3. 從 Github 找出實用資源流程**

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LGRNQS_gkfsZWcmxOVe%2F-LGTcUOYh3_0GJaqbbJ8%2F-LGTcZ_FsPnF25yH3pjG%2Fimage.png?alt=media&token=b3c8b1c0-1b54-42e4-a9a7-d377e3a0a5ee)

From : https://github.com/

# ​ {#undefined}

## **環境安裝 - \(7/3/2018\)** {#jing-an-7-3-2018}

**1. Git 環境安裝**

* ​[**Git 官網**](https://git-scm.com/)​

**2. Windows - 命令提示字元教學**

* 基本 command 操作指令

  * cd ······· \(切換工作路徑\)

  * mkdir ······· \(新增資料夾\)

  * ls ······· \(列出清單\)

  * touch ······· \(產生新檔\)

**3. Git 環境設定**

command:`git config --global user.email "作者的 email" git config --global user.name "作者的 name"`

ex :`git config --global user.email "avantsao@gmail.com" git config --global user.name "avantsao"`

check:`git config --list | grep -i user`

​

### _Git Official Site_ {#git-official-site}

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LGRNQS_gkfsZWcmxOVe%2F-LGTcUOYh3_0GJaqbbJ8%2F-LGTckx9kUcQ6k-KmQaZ%2Fimage.png?alt=media&token=9f189740-2ebf-42c8-a84f-54c7b44b2c42)

from : https://git-scm.com/

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LF51Utz1hhNmMPRJ4HM%2F-LF5CJVzcEkZKE4Svm-V%2F-LF5CYKR2uPvEq0o-b8z%2Fimage.png?alt=media&token=ebce8e06-ac28-4615-8295-0c44dc2085cf)

​

​

## Git 基礎操作\(上\) {#git-ji-cao-zuo-shang}

1. 教學大綱圖

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LGRNQS_gkfsZWcmxOVe%2F-LGTcUOYh3_0GJaqbbJ8%2F-LGTcwCvhvgyQyjVV2OO%2Fimage.png?alt=media&token=47368fe4-4a8c-4599-bb24-b823763983de)

Git commit process

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LF51Utz1hhNmMPRJ4HM%2F-LGPk6rauGJspRmmaUcJ%2F-LGPk9-MgdYPEYaEIeVF%2Fimage.png?alt=media&token=ff27ad56-fb37-4165-837f-db9060107843)

2. git init - 安裝數據庫

3. 工作目錄、加入索引、提交版本流程介紹

4. 基礎指令教學流程

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LGRNQS_gkfsZWcmxOVe%2F-LGTcUOYh3_0GJaqbbJ8%2F-LGTd-eg8s_lx_x9HFJ9%2Fimage.png?alt=media&token=849c08ca-bf4a-4e0a-8c9e-62b905f52639)

Commit to local repository

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LF51Utz1hhNmMPRJ4HM%2F-LGPv0Kv2ZUFXPJQHzRR%2F-LGPv5P2G5jhOgpF7BRt%2Fimage.png?alt=media&token=2a509bec-a3d4-4ba4-b39e-b251e9a4b176)

5. git push - 推送數據庫到 Github`git add . git commit -m 'release msg' git remote add origin https://github.com/avantsao/test.git git push -u origin master`

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LGRNQS_gkfsZWcmxOVe%2F-LGTcUOYh3_0GJaqbbJ8%2F-LGTdAc_40fPyGckC4MS%2Fimage.png?alt=media&token=5d23178e-8f48-475f-bd33-a925bb913e1c)

Push to remote repository

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LF51Utz1hhNmMPRJ4HM%2F-LGPv0Kv2ZUFXPJQHzRR%2F-LGPvDsXcpYZhBbsNCz8%2Fimage.png?alt=media&token=6ad2e6e9-e862-4400-a9c5-f70731cb8070)

​

# ​ {#undefined-1}

## Git 基礎操作\(下\) {#git-ji-cao-zuo-xia}

1. 工作狀態還原技巧分享

2. gitignore - 忽略檔案

* ​[gitignore 大全](https://github.com/github/gitignore)​

3. 指令參考

​

# ​ {#undefined-2}

## Git 分支 \(branch\) {#git-fen-zhi-branch}

1. 分支簡介

2. HEAD - 瞭解目前所在位置

3. git branch - 分支創立

4. git merge - fast-forward

5. git merge - 自動合併

6. git merge - 解決衝突

7. git tag - 標籤

8. git stash - 暫存檔案

​

# ​ {#undefined-3}

## Git、Github 團隊協作篇 {#gitgithub-zuo-pian}

1. git remote - 遠端數據庫

2. git pull - 下載遠端數據庫

3. git pull - 衝突

4. Github Pages - 存放網頁空間流程

5. 小型團隊分支協作

6. git pull = git fetch + git merge  




