# URL
### ◎URLとは  
 - URLとは、インターネット上でのwebサイトやファイルの場所や情報の住所になります。
 - URLは、「Unifrom　Resource　Locator」の略になります。
<br>　　
### ◎URLの形式  
<br>　　
&emsp; 　　　　 ( URLの例 ）http://www.hamser-plus.co.jp/blog/animal
<br>
<br>
&emsp;　　　〇プロトコル  
&emsp;　　　　・プロトコルとは、通信での送受信のルールになります。  
&emsp;　　　　・（　URLの例　）　のプロトコルは、「　http　」になります。
<br>
<br>
&emsp;　　　〇スキーム  
&emsp;　　　　・スキームとは、どの方法で通信するか決めているものになります。  
&emsp;　　　　・（　URLの例　）　のスキームは、「　http:// 」になります。  
&emsp;　　　　・（　URLの例　）　でいうと「httpで通信する」と決めている事なります。
<br>  
&emsp;　　　〇ホスト名  
&emsp;　　　　・ホスト名とは、 インターネット上でのコンピューターの名前になります。  
&emsp;　　　　・（　URLの例　）　のホスト名は、「　www 」になります。  
<br>
&emsp;　　　〇ドメイン  
&emsp;　　　　・ドメインとは、IPアドレスを、人間が判別しやすい文字列に置き換えたものであり、  
&emsp;　　　　　インターネット上でのコンピューターの住所になります。  
&emsp;　　　　・（　URLの例　）　のドメインは、「　hamser-plus.co.jp 　」になります。   
<br>
&emsp;　　　〇ディレクトリ  
&emsp;　　　　・ドメインとは、サーバー内にデータを保存しておく場所になります。  
&emsp;　　　　・（　URLの例　）　のディレクトリは、「　blog 　」になります。
<br>
&emsp;　　　〇ファイル名  
&emsp;　　　　・ファイル名とは、URLが最終的に表示される形式になります。  
&emsp;　　　　・（　URLの例　）　のディレクトリは、「　animal 　」になります。  
<br>
***
# クエリ文字文字列
### ◎クエリ文字列とは  
&emsp;　　　　・クエリ文字列とは、URLの末尾から「？」で始まる文字列のことになります。   
&emsp;　　　　・クエリ文字列は、広告の効果を測定したり、集客でいいサイトを判断する等で  
&emsp;　　　　　使用されます。  
&emsp;　　　　・クエリ文字列は、URLパラメータやクエリパラメータとも呼ばれています。      
<br>
<img src="https://www.kwm.co.jp/media/2021/05/image10.png" align="right" width="90%">  
<br>
<br>
<br> 
<br>  
<br>
&emsp;　　　　　　　　　　　　　　　　　　　　     　　　　　　　　　クエリ文字列の参考画像　　　　
<br>
<br>

***
# パス変数  
### ◎パス変数とは  
&emsp;　　　　・パス変数とは、パソコンの環境変数という動作設定項目の一つになります。  
&emsp;　　　　・パス変数は、パスという実行ファイルまでの経路をパス変数に認識させる事により  
&emsp;　　　　　コマンド入力の際に実行ファイル名のみで実行が出来るようになります。  
&emsp;　　　　・パス変数は、パスパラメーターとも呼ばれています。  

***


>[!NOTE]
>### ◎クエリ文字列とパス変数の違いについて
>　〇見た目の違い
>```
>①　http://zenn.dev/search
>②　http://zenn.dev/search?=Laravel
>```
>　　　　・パス変数(パスパラメーター)は①・②の「　serch　」にあたります。  
>　　　　・クエリ文字列(クエリパラメータ)は②の「 ?q=Laravel 」にあたります。  
>　 〇用途の違い                          
>　　　　・パス変数（パスパラメーター）は、情報収集で情報を区別するために必要な情報になります。  
>　　　　・クエリ文字列(クエリパラメータ)は、情報収集で情報を取得する方法になります。
> 
***
# HTTPメゾット　
### ◎HTTPメゾットとは　　
&emsp;　　  　　・HTTPメゾットとは、クライアント（PCやスマホ）からサーバにやりたい事を依頼する方法になります。　　
<br>
### ◎主に使われるHTTPメゾットの種類と意味　　
<br>
<br>

| HTTPメゾット | 意味 | 例 |
|:---:|:---:|:---:|
|GET |URLごとに指定された情報の取得を行う|・動画の取得・Webページの取得 |
|POST |リソースに対する新規追加を行う |・SNSのアカウント作成する・Facebookでコメントを投稿する |
|PUT|リソースに対する新規追加、更新を行う |・自分の投稿内容を編集する・掲示板でページを作成する |
|PATCH|リソースの部分更新を行う|・ユーザ情報だけを変更する・記事のタイトルだけを更新する|
|DELETE|リソースの削除を行う |・記事を削除する・投稿を削除する|

<br>
<br>　　

>[!NOTE]
>### ◎POST・PUTの違いについて
>　　　〇POST  
>　　　　・リソース作成する時、リソースのURLを指定出来ないです。  
>　　　　・サーバー上のリソースに対してデータを送信するために使用します。  
>　　　　・送信するデータは暗号化されており、大量のデータを送信する事が出来ます。   
>　　　〇PUT  
>　　　　・リソースを作成する時、リソースのURLをクライアント側が識別番号を指定出来ます。  
>　　　　・指定したリソースがある場合は、送信したデータを丸ごと書き換えます。  
>　　　　・指定したリソースがない場合は、新規作成されます。
>  
***  
# リクエストヘッダー  
### ◎リクエストヘッダーとは  
&emsp;　　　　・リクエストヘッダーとは、クライアント( PCやスマホ ）からサーバーにリクエストを送信する時、  
&emsp;　　　　　リクエストの内容を補足する情報の事になります。  
&emsp;　　　　・リクエストヘッダーの情報の形式は「　フィールド名　と　値　」で表されます。
<br>
<br>
<img src="https://s3.ap-northeast-1.amazonaws.com/wraptas-prod/shukapin-note/4ee7a7df-2824-49ae-be4c-878d8166676d/6e7f9e8d0612ded8829475f664a67d2e.svg" align="center" width="80%">  
<br>  
<br>
***  
# HTTPステータスコード  
### ◎HTTPステータスコードとは  
&emsp;　　　　・HTTPステータスコードとは、HTTPレスポンスに含まれるWebサーバーの処理結果を表現する  
&emsp;　　　　 3桁の数字の事になります。  
### ◎HTTPステータスコードで主に使われているコード  
<br>

| HTTPステータス | 意味 | 状態 |
|:---:|:---:|:---:|
|200|リクエストが正常に処理できた事|正常 |
|201 |リクエストが成功してリソースの作成が完了した事|正常 |
|400|一般的なクライアントエラーの事 |エラー |
|404|Webページが見つからない事|エラー|
|500|何等かのサーバ内の起きたエラーの事 |エラー|　

<br>  

***
# HTTPレスポンスヘッダー  
### ◎HTTPレスポンスヘッダーとは
&emsp;　　　　・HTTPレスポンスヘッダーとは、HTTPリクエストに対してサーバからクライアントに  
&emsp;　　　　　返すHTTPレスポンスの一部になります。　　　　　  
&emsp;　　　　・HTTPレスポンスヘッダーは、データ本体の前に送られてくる、各種の状態を示す情報が  
&emsp;　　　　　 入れられている部分です。

### ◎代表的なHTTPレスポンスヘッダー  
<br>

| HTTPレスポンスヘッダー | 意味 |  
|:---:|:---:|
|コンテンツタイプ(Content-Type)|データがHTMLなのか画像なのかや、文字コードなどの情報| 
|再利用期限　(Expires) |取得したデータを再度サーバーに問い合わせなくもブラウザが再利用していい期限|
|データの最終更新日時(Last-Modified)|HTMLや画像などがいつ更新されたものかの情報|
|エンティティ情報　(ETag)|ファイルの場所ID、ファイルのサイズ、更新チェック情報|
|キャッシュ制御（Cache-ControlやPragma)|ブラウザや通信を橋渡しするプロキシが、データのキャッシュをどう扱うかの情報|
|接続状況（Connection）|接続を持続するのかや毎回接続を切断するのか等の情報 |
|移動先（Location）|リクエストと違う場所からデータを取得するように示す指示|

***

# HTTPレスポンスボディ
### ◎HTTPレスポンスボディとは
&emsp;　　　　・HTTPレスポンスボディとは、HTTPリクエストに対してサーバからクライアントに  
&emsp;　　　　　返すHTTPレスポンスの一部になります。　　　　　  
&emsp;　　　　・HTTPレスポンスボディは、リクエストされたURLに対するHTMLや画像などの  
&emsp;　　　　　データが記載されます。

***

# JSON　　
### ◎JSONとは  
&emsp;　　　　・JSONとは、JavaScriptで値を取り扱うためのドキュメント規格になります。  
&emsp;　　　　・JSONは、「　JavaScript Object Notification　」の略になります。  
&emsp;　　　　・JSONは、JavaScriptだけでなくPHPやPython等のその他の言語観のやりとりでも、  
&emsp;　　　　　使えます。  

### ◎JSONをメリット  
&emsp;　　　　１．テキストベースで軽い事  
&emsp;　　　　　　・テキスト量が少なく、高速な通信が必要な場合、とても有効です。  
&emsp;　　　　２. 解析しやすい事  
&emsp;　　　　　　・JSONは、値と項目のペアで記載するため視覚的に確認がしやすいです。  
&emsp;　　　　３. JavaScriptとの相性が良い事  
&emsp;　　　　　　・フロントエンド開発において、「通信におけるデータフォーマット」と  
&emsp;　　　　　　　「ブラウザ内でのデータ保持」の両方に適用できます。  

### ◎JSONの書き方  
&emsp; 　〇基本の書き方   
&emsp; 　　　　・JSONは、｛｝の中にキーと値をコロンで区切って記述します。  
&emsp; 　　　　・キーは必ずダブルフォーテーションで囲む必要です。  
```
{"key" : "value"}
```
&emsp; 　　　　・カンマで区切ると、キーと値の組み合わせを複数記述できます。
```
{"key1" : "value1","key2" : "value2"}
```
### ◎JSONが対応しているデータ型  
&emsp; 　　　　1.文字列  
&emsp;　　　　　・文字列は、ダブルクォーテーション(")、バックスラッシュ(\)以外の文字であれば  
&emsp;　　　　　　日本語でも入力ができます。
```
{"name" : "tanaka"}
```             
&emsp; 　　　　2.数値  
&emsp; 　　　　 ・数値は、ダブルクォーテーションで囲むと文字列扱いになるので、囲まず  
&emsp;　　　　　　入力します。
```
{"id": 1}
```
&emsp; 　　　　3.null  
&emsp; 　　　　 ・nullは、値がない事をnullで指定します。  
```
{"name" : null }
```
&emsp; 　　　　4.真偽値  
&emsp; 　　　　 ・真偽をtrueをまたはfalseで指定します。  
```
{
　"active_flag" : true,
  "delete_flag" : false,
 }
```
&emsp; 　　　　5.オブジェクト  
&emsp; 　　　　 ・オブジェクトを｛｝で指定する事が出来ます。 
```
{
　　"user_info": {
    "user_id": "A1234567",
    "user_name": "Yamada Taro"
  }
}
```
&emsp; 　　　　 6.配列  
&emsp;　　　　　・配列を［］で指定します。  
&emsp;　　　　　・配列の要素には、文字列、数値、null値、真偽値、オブジェクト、配列すべてを使用出来ます。
```
{
  "color_list": [ "red", "green", "blue" ],
  "num_list": [ 123, 456, 789 ],
  "mix_list": [ "red", 456, null, true ],
  "array_list": [ [ 12, 23 ], [ 34, 45 ], [ 56, 67 ] ],
  "object_list": [
    { "name": "Tanaka", "age": 26 },
    { "name": "Suzuki", "age": 32 }
  ]
}
````
### ◎JSONの例 
```
｛
　 "student_list" : [
     { "name" : "中田" ,"age" : 12 , "Birthplace" : "大分県"},
     { "name" : "溝口" ,"age" : 11 , "Birthplace" : "福岡県"},
　   { "name" : "薬真寺" ,"age" : 10 , "Birthplace" : "熊本県"},
     { "name" : "山下" ,"age" : 12 , "Birthplace" : "福岡県県"}
　　］
｝
```




