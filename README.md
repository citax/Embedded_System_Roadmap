# Embedded System Roadmap

## Gömülü Yazılım Yol Haritası

> Gömülü yazılım yol haritası `TR`

Bu kod deposu gömülü sistemler üzerine çalışmak isteyenler için, kişisel tecrübe ve keşkelerin sonucu olarak ortaya çıkmıştır. Bu uçsuz bucaksız internet aleminde daha faydalı ve üstadım olarak göreceğim kişilerin veya toplulukların hazırladığı yol haritaları olabilir. Lütfen kendi kaynak araştırmanızı yapınız! Ayrıca daha ayrıntılı yol haritalarının yanında bu yol haritası basit ve direkt hedefe ulaşmayı amaçlamaktadır. -Citak

Her bölümün sonunda bırakacağım kaynaklara lütfen kendiniz de zaman ayırarak bakınız. Bırakılan kaynaklar dışında kendi kaynaklarınızı da lütfen edininiz. Eksik gördüğünüz veya eklense ne de tatlı olur dediğiniz şeyleri lütfen eklemekten çekinmeyiniz!

    Lütfen ama lütfen Tutorial girdabına yakalanmayınız. En güzel öğrenme uygulamalı öğrenmedir. 
    Giriş seviyesine ulaştıktan sonra direkt projelere dalınız. Unutmayın sizden önceki herkes bu işi gerçekten bir şey yaparak öğrendiler. 
    
[! George Hotz Tavsiyesi !](https://www.youtube.com/watch?v=NjYICpXJ03M)


[*Ayrıntılı Yol Haritası*](https://github.com/m3y54m/Embedded-Engineering-Roadmap)

### 1. **C**

`C` yazılım dili ve tarihçesi hem yazılım dünyası hem de gömülü sistemler için oldukça önemlidir. Her şey C dilinin syntax yapısını anlamak ve kullanmayı öğrenmekle başlar. Üniversitede aldığınız yarım yamalak yazılım derslerine güvenip, "Ben C dilini biliyorum." gibi manasız laflar söylemeyiniz. Buz dağının görünmeyen taraflarına da hakim olmak için lütfen oturup herhangi bir üstadın hazırladığı C kitabını okumaya ve örneklerini kendi başınıza yapmaya çalışınız. 

`C` dili bir araçtır ve bu unutulmamalıdır. Bu yazılım araçları belli amaçlar için kullanılır ve o amaçlar uğruna kullanılırken asıl öğrenme eylemi yaşanır. Başta C kendi başına manasız gelse de bir noktaya geldiğinizde ve öğrendiklerinizi gömülü yazılımda kullanmaya başladığınızda bazı şeyleri otutturmaya başlayacaksınız. Acele etmeyiniz ve bunun uzun bir yol olduğunu kabul ediniz.

#### Kaynaklar

**NOT:** Aşağıda verilen kitaplar internette bir çok sitede pdf halinde bulunabilmektedir. Üstadlara olan saygımdan dolayı bağlantılarını buraya bırakamıyorum.

- The C Programming Language Ritchie & kernighan 
- C How to Program 8th - 9th Edition Deitel & Deitel

### 2. **Mikroişlemci - Mikrodenetleyiciler**

Mikroişlemci - Mikrodenetleyiciler gömülü yazılımın üzerinde koştuğu en küçük donanımsal entegrelerdir. Mikroişlemci - Mikrodenetleyicilerin neden kullanıldığını ve temelde ne işe yaradığını öğrenmeden hiçbir şekilde ilerleme kaydedilemez. Bu kısım çoğunlukla atlanır. `Arduino` denen çocuk oyuncağının getirdiği basitlik ile bu kısım her zaman basitliğin arkasında kalmıştır.

Lütfen yazılım desteği oldukça iyi olan ve her şeyin önünüze altın tepside sunulmadığı bir `Texas Inc. - Tiva` veya `STM32` bir mikrodenetleyici (geliştirme kartı) edininiz. 

#### Kaynaklar

- CCS C ile PIC Programlama Serdar ÇİÇEK
- Digital Design and Computer Architecture Harris & Harris

.

     Başlangıç için bu C dili ve Mikroişlemci bilgisi edinilmelidir. 
     Bundan sonra yazılımsal konseptler ve ayrıntılar öğrenilmelidir.


>Devam edecek.. 


-----------------------------------
> Embedded system road map    `EN`



## Projeler

1. EEPROM Kütüphanesi

### EEPROM Kütüphanesi Projesi

#### Proje Tanımı
Bu proje, bir EEPROM kütüphanesi geliştirme üzerinedir. Kütüphane aşağıdaki özellikleri içermelidir:

- UART üzerinden gelen **uint8_t**, **uint16_t**, ve **uint32_t** türündeki karışık verileri EEPROM'a yazabilme.
- EEPROM'un doluluk oranını hesaplama.
- EEPROM'u sıfırlama.
- EEPROM'da hangi registerlara veri yazıldığını listeleme.

Proje, stajyerlerin gömülü sistemlerde EEPROM kullanımı ve veri yönetimi konularında pratik yapmalarını amaçlamaktadır.

---

#### Donanım Gereksinimleri
- Bir mikrodenetleyici (Tiva veya STM32)
- UART iletişim arayüzü
- Harici veya dahili bir EEPROM modülü

#### Yazılım Gereksinimleri
- C veya C++ dili
- Mikrodenetleyiciye uygun geliştirme ortamı (Code Composer Studio, STM32CubeIDE)
- EEPROM sürücüsü (I2C veya SPI tabanlı)

#### Proje Teslimi

##### Teslim Edilmesi Gerekenler
1. EEPROM kütüphanesinin kaynak kodu.
2. Kütüphanenin kullanımını açıklayan bir README dosyası.
3. Projeye dair github reposu.
4. Kütüphaneyi test etmek için örnek bir uygulama kodu.

#### Notlar
- Kütüphane **modüler** ve **yeniden kullanılabilir** olacak şekilde yazılmalıdır.
- Kod, **yorumlarla açıklanmış** olmalıdır.
- Kod standartlarına uygunluk önemlidir (ör. değişken isimlendirme, kod formatlama).

        Başarılar!


