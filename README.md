# BKM Key Generator Tool
Public - private key çiftini üretmek için hazırlanmışdır.Ekteki RsaKeyGeneratorEXE.rar dosyasını indirerek , RsaKeyGenerator.exe 'yi çalıştırınız.Açılan ekranda Private Key oluşturma kategorisinde;  <br>
- PFX dosya ismi alanında istenilen sertifika ismi verilir.
- Şifre alanında ise yaratılacak olan sertifikanın şifresi yazılır.
- Key Size’da 1024 – 2048 seçeneklerinden biri seçilir.
Generate New Key butonuna tıklayarak ,dizine kaydettiğinizde .pfx formatında private key sertifikası oluşturulur. 

Public key görüntüleme kategorisinde;
- Private Keyinizin Şifresi alanında private keyinizin şifresini girip,show key information butonuna tıklayarak, oluşturduğunuz pfx dosyasını seçtikten sonra ekranda örnek olarak aşağıdaki şekilde public keyiniz oluşacaktır.

-----BEGIN PUBLIC KEY----- <br>
MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQCgbFKcsF2OGimsqheG6Eiv8I+p
pyQs69iy1qqXqb7FexdWNGYpygKR6qXSl6USogorwytMLZcWnFRaat81cFn1ZCsR
m0mRDX3SXh5tQL5RZrGaK5SlnQiFQq9eudv59nMU6ugkAZt62SaaYxc/nJOVXJpG
ZWUIVxvqQ0SN5Dh/OQIDAQAB <br>
-----END PUBLIC KEY-----

Public - Private key çiftini üretmiş oldunuz.Public key bilgisini BKM firmasına paylaşabilirsiniz,private key bilgisi (şifre,pfx dosyası) ise sizde kalmaktadır.Entegrasyonda sign'ı verify edebilmeniz için BKM'nin public key bilgisini kullanmanız gerekmektedir.Ekte BKMPem.rar  dosyasından BKM'nin public keyine ulaşabilirsiniz.
