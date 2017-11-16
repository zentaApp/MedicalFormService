# MedicalFormService
医療クリニックで、患者に渡す検査結果票を簡単に作成するwebサービス

# サービスの利用想定
1	検査後、医師がPC上で、ブラウザでサービスにアクセスする。
	↓
2	サービス画面で、画像アップと検査結果を入力する
	↓ 
3	ブラウザの画面を印刷して、プリンターで出力する
	↓
4	出力した「検査結果」は患者様に渡す

対象ブラウザ:chrome、IE、Safari


# アーキテクト

#フロント
Bootstrap4
TypeScript Anguler 2

#バック
Play Framework
MySQL

#CI環境
Gradle
Slack

# 環境
browser -> DNS -> AWS EC2 nginx -> nginx ->

#開発環境
Eclipse
WebStorm

