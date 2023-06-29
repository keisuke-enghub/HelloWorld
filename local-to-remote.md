# ローカルリポジトリからリモートリポジトリへ上げる方法

【手順】  
１．リモートリポジトリの作成(ブラウザ上で)  
２．リモートリポジトリの追加(管理？対象の追加？)  
　> git remote add リモート名　リモートURL  
　*リモート名は一般的に origin らしい   
２’ 追加されているか確認  
　> git remote -v  
３．リモートリポジトリにプッシュ  
　git push リモートリポジトリ名　ローカルリポジトリ名(ブランチ名？？)  

参考）  
・【 GitHub 】ローカル作成したリポジトリをリモートに「Push」するまで！  
　https://qiita.com/Futo_Horio/items/4d669f695680bc13d5fa  
・【Git】リモートリポジトリの追加・変更・削除・リネームする方法｜git remoteコマンド  
　https://web-engineer-wiki.com/git/git-remote/  
・プロダクトに名前を付けるときに気を付けたいこと  
　https://qiita.com/dtan4/items/639928bcfc6ac0a69a57  
・git pushで自分のレポジトリへのアクセスが403で拒否される対処法 Remote: Permission to user1/repo denied to user2  
　https://qiita.com/mtc465/items/c2e8472f797e9f5bbc43  