# rime-shanren3 

# 部分文件介紹

## 0--shanren00.dict.yaml  
此文件是最初的碼表，後來改用濾鏡顯示相關信息，所以該文件改作數據庫處理原始數據。

```
   過	【eo】_00_｛3@2｝〖EgOL〗_〔冎口辶〕『CJK』〘2k〙	112999   
   齶	【eoov】__｛5@4｝〖EciOOVeZ〗_〔齒口口二ㄅ〕『CJK』〘4c〙	600   
   齶	【eoovzc】__｛5-c｝〖EciOOVeZ〗〔齒口口二ㄅ〕『CJK』〘4C〙	-4
```

`〔〕`內是拆分字根。

`〖〗`內是由字根轉成的全息碼。

`【】`內是簡碼或常規編碼。

`｛｝`內是字根數及小碼信息等，其中`@\d`表簡碼數，`=`表實際編碼數等於字根數。

`00` `01` 是對重碼的標序。

`■` 表示該字拆分來自山人原始程序之外。

`〘2k〙`等等，表示`【】`中編碼的形成方式。`a`表一般的簡碼，b表常規編碼就是簡碼，`c(de)`表簡碼與常規編碼位置極近、或是新加，`k`表示字根、特碼或有多個簡碼等。

`_〔` 表示該編碼用於連打。

字頻中標爲`負數`的，表示該編碼已有簡碼。

