# プロダクトのタイトル
居住支援　福祉施設マスターファイル編集削除処理の追加


## プロダクトの紹介
居住支援　福祉施設マスターファイル（編集、削除）

## 工夫した点，こだわった点
特にありません。

## 苦戦した点，共有したいハマりポイントなど
- UPDATEでFatal error: Uncaught PDOException: SQLSTATE[HY093]: Invalid parameter number: number of bound variables does not match number of tokens in C:\xampp2\htdocs\課題７PHP\Housing_support_update.php:49 Stack trace: #0 C:\xampp2\htdocs\課題７PHP\Housing_support_update.php(49): PDOStatement->execute() #1 {main} thrown in C:\xampp2\htdocs\課題７PHP\Housing_support_update.php on line 49
のエラーメッセージが表示されます。
私の力ではこのバグを解消することはできませんでした。


DBで絡むの追加を試みましたが、MySQL のメッセージ: ドキュメント#1292 - Incorrect datetime value: '0000-00-00 00:00:00' for column `gsacf_d08_13`.`housing_support_table`.`UPDATE` at row 1
が表示されカラムの追加を行うことができませんでした。