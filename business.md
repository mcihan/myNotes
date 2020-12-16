# 3D

## 3 domain nedir ?

**Acquirer Domain** : İş yerlerini ve bunların çalıştığı bankaları bulundurur.  
 Components:  
- MPI (Merchant Server Plug-in), 
- 3DS Requestor Envionment (3DS Requestor, 3DS Server, 3DS Client)
- 3DS Integrator  

**Issuer Domain** : Ödemede kullanılan kartlar ve bu kartların basıldığı bankaları bulundurur.  
Components: 
- ACS ( Access Control Server)

**Interoperability Domain** : Bu iki domain arasında iletişimi sağlar ve kart bileşenlerinin şemasını tutar.   
Components: 
- DS (Directory Server),
- DS CA (Directory Server Certificate Authority)
- Authentication History (AH)


## Issuer bankalar ?


# ACS ( Access Control Server)
İlgili issuer bankaların belirlediği kurallar ve yöntemlerle kart hamillerinin doğrulanmasını sağlar.

- İlgili kartın kayıtlı ve doğrulanabilir olup olmadığını kontrol eder.
- Issuer bankanın belirlediği yöntemlerle kart hamilini(card holder) doğrular. (**Challenge**)

3DS 2.0'da Challenge iki aşamada gerçekleşir;
- Bir risk doğrulaması yaparak **Frictionless** akışları sonrası işlemi **challenge** a girmeden tamamlayabilir. 
- Sadece ödeme işlemleri için değil, **non-payment** içinde 3DS doğrulama akışı gerçekleştirilebilir.


# DS (Directory Server)


## 3D 2.0 daki değişiklikler ?