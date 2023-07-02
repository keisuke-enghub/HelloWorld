# Branchを切るとは？  
ブランチを切って、マージするまでをやってみる  

*とりあえず状態を確認してみる*  
＞git status   
On branch master  
＞git branch  
* master  
マスターブランチが１つだけあり、現在はそのマスターブランチにいるみたい。  

＞git checkout -b develop  
これでmasterブランチからdevelopブランチに枝分けさせて、 -b　で追加でブランチを移動しているみたい。  
* develop
  master  
  remotes/origin/HEAD -> origin/master  
  remotes/origin/master  
  


# 参考
git コマンド branchの作り方  
https://qiita.com/TetsuTaka/items/5ab227a8bd2cd7106833  

ブランチ切って更新してマージするまでの流れ  
https://qiita.com/shuntaro_tamura/items/6c8bf792087fe5dc5103  

