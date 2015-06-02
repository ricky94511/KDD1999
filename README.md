# KDD1999資料分析

1.data preprocessing   <br />
-----------------------------------------------------------------------------
在資料前處理方面，我們使用Ｒ做一些資料格式的轉換，我們將protocol_type.service.attack_type <br />
等欄位都轉成數值，因考量到attribute眾多，我們會先使用決策樹做變數選擇找出就具有指標之變數 <br />
從決策樹的rule看出用來分類的最主要是兩個變數


2.choose  K   <br />
-----------------------------------------------------------------------------



3.classification model   <br />
-----------------------------------------------------------------------------
 第一個我們使用decesion tree來做分類，當只使用兩個attribute時 <br />
 
 | true  | false |
 | ------| ----- |
 | 967140| 12546 |
 
 | First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
