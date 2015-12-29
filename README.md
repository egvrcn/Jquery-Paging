# Jquery-Paging
Jquery Paging with Server Side

Örnek bir server remoting datatable controller tarafı. Öncelikle istenen parametrelere göre tablo verileri çekilir.
Herhangi bir filtreleme işlemi varsa bu tablo üzerinden filtreleme yapılır. 
Gelen paramModel ifadelerine göre skip ve take işlemleri uygulanır.
Datatable'ın bizden istediği yapıda bir veri yapısı oluşturulur. Yapı diziye çevirilir.

jQueryDataTableParamModel sınıfı içerir. Bu sınıf client tarafından hangi sayfaya gidildiği, 
neyin filtrelendiği gibi bilgileri hafızasında tutarak controllera bildirir.
