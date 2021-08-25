# カンバンボードアプリ
短期間のタスクを管理するtoDOアプリです。
スケジュール管理能力を鍛える目的で、タスクの作業時間を計測できるようにしてあります   
アプリURL
http://okanbanboard.com/
# 使い方
### タスク作成
<img src="https://user-images.githubusercontent.com/73730180/130543603-d8ee9771-63fe-4f20-8744-d5aa7f2217ed.jpeg" width="250px">.  
+ボタンをクリックしタスク名を入力して作成をクリックするとカード（タスク）を作成できます。
### タスク削除
<img src="https://user-images.githubusercontent.com/73730180/130544270-68b28790-93ee-4391-b545-ae2f4e4a49d0.jpeg" width="250px">
ゴミ箱マークをクリックして削除をクリックするとカード（タスク）を削除できます。
   
### タスクの進行状況変更

<img src="https://user-images.githubusercontent.com/73730180/130545034-0a84e4f4-b7b9-4011-89fa-0727bec29300.jpeg" width="1439">

カード（タスク）をドラッグし、適当な進行状況にドラッグすることでカードが移動します   
進行中のカラムにドラッグすると、カードの横の時間が経過します   
タスクのカラムにドラッグすると、カードの経過時間がリセットされます   
その他のカラムにドラッグすると、カードの経過時間がストップします   


### タスクの検索
<img width="1439" alt="スクリーンショット 2021-08-24 12 11 16" src="https://user-images.githubusercontent.com/73730180/130549954-7e82d0de-7e9d-4351-8aae-7a481db08697.png">

右上の検索欄に入力することで、該当のタスクを検索することができます。

# 使用技術
### アプリ
・HTML/CSS   
・Ruby on Rails   
・TypeScript/React   
・MySQL   

### インフラ（AWS）
・VPC   
・EC2   
・RDS   

### その他
・AWS環境のコード化：CloudFormation   
・CI/CDツール：Jenkins   
・インフラ環境の自動構築ツール: Ansible   
・インフラ環境のテスト： ServerSpec   

# 機能一覧
・カード（タスク）のCRUD機能   
・カードの検索機能    
・カードの時間測定機能    
・Cookieによるセッション管理    
※Cookieを削除しますとデータが保存されませんのでご注意ください。

# デプロイ方法
### アプリのソースコード一覧
・フロントエンド(https://github.com/kosukeoku/kanbanboard-front)   
・バックエンド(https://github.com/kosukeoku/kanbanboard-back)   
### デプロイ手順
デプロイ手順は以下のURLの方法で実施
https://github.com/kosukeoku/deploy
