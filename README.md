# Online Satış Veri İncelemesi
Bu proje online satıştaki verilerin incelenmesini içermektedir.

## **Proje Ozeti** 
- 12 farklı ülkenin satış verileri incelenmiştir.
- Analiz edilen veri setinde eksik deger (null) bulunmaktadır.
- Veriler, InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country, Discount, PaymentMethod, ShippingCost, Category, SalesChannel, ReturnStatus, ShipmentProvider, WarehouseLocation, OrderPriority bilgilerini icermektedir.


## **Verinin Genel Yapisi**
Veri Setinin Sutunlari (Toplam 17 sutun):

|  Column                |    Non-Null | Count    | Dtype  |
|---  | ------             |       -------------- | -----  |
| 0    |  InvoiceNo             |   49782  | non-null  |   int64  |
| 1    | StockCode              |   49782   | non-null  | object |
| 2    |  Description           |   49782   | non-null     |object |
| 3    |   Quantity             |   49782   |non-null    | int64  |
| 4    |  InvoiceDate           |   49782   |non-null     |object |
 |5    |   UnitPrice            |   49782   | non-null    | float64|
 |6    |   CustomerID           |   44804   | non-null    | float64|
| 7    |   Country              |   49782   | non-null    | object |
| 8    |   Discount             |   49782   |non-null     |float64|
 |9    |   PaymentMethod        |   49782   | non-null    | object |
 |10   |  ShippingCost          |   47293   | non-null    | float64|
| 11   |  Category              |  49782    |non-null    | object |
 |12   |  SalesChannel          |  49782    |non-null    | object |
| 13   |  ReturnStatus          |  49782    |non-null   |  object |
| 14   |  ShipmentProvider      |  49782    |non-null     |object |
| 15   |  WarehouseLocation     | 46297    |non-null    | object |
| 16   |  OrderPriority         | 49782    |non-null   |  object |


**Veri tipi dagilimi:** float64(4), int64(2), object(11)

**Bellek kullanimi:**  6.5+ MB

## **One Cikan Bulgular**
- **Kayıp Değerler:** Analiz edilen veri setinde kayip deger tespit edilmiştir.
- En çok **White Mug** ürününden satılmıştır.
- En çok satış yapılan kategori **Furniture** dır.

## **Projenin Amaci ve Yontemi**
Bu projede, online satıştaki bazı verilerin karsilastirilmasi hedeflenmistir. Kesifsel veri analizi (EDA) yontemleri kullanilarak veri incelenmis ve sonuclar gorsellestirilmistir. 

Kaggle Linki : https://www.kaggle.com/code/damlaentrk/online-sales



