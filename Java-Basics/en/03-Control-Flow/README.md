## 03-Control-Flow 🚦

Bu klasör, Java'nın kontrol yapıları olan `if-else`, döngüler (`for`, `while`, `do-while`) ve `switch` yapılarını öğrenmek için temel rehberdir. 👨‍💻 Bu yapılar, programın akışını yönetmenizi sağlar ve belirli koşullara göre farklı yollar izlemenize yardımcı olur. Aşağıdaki dosyalar, bu yapıları örnekler ve egzersizlerle açıklamaktadır.
### 📝 İçerik

### 1. IfElseExample.java ❓🔀

**If-else yapısı**, belirli koşullara göre farklı işlemler gerçekleştirmeyi sağlar. Eğer bir koşul doğruysa bir blok çalışır, aksi halde başka bir blok çalışır.

**Örnek Kod:**
```java
int number = 10;

if (number > 0) {
    System.out.println("Sayı pozitiftir.");
} else if (number == 0) {
    System.out.println("Sayı sıfırdır.");
} else {
    System.out.println("Sayı negatiftir.");
}
```

🧑‍🏫 **Açıklama:** Bu örnekte, `if-else` yapısı ile bir sayının pozitif, negatif ya da sıfır olup olmadığını kontrol ediyoruz.

🎯 **Egzersiz:**
- Bir sayı girip pozitif mi negatif mi olduğunu yazdıran bir program yazın.
- Kullanıcının yaşına göre "Çocuk", "Genç" ya da "Yetişkin" olduğunu belirleyen bir program geliştirin.

---

### 2. Loops.java 🔄

**Döngüler** belirli bir işlemi tekrar tekrar gerçekleştirmek için kullanılır. Java'da en yaygın kullanılan döngüler `for`, `while` ve `do-while` döngüleridir.

**Örnek Kod (For Döngüsü):**
```java
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```

**Örnek Kod (While Döngüsü):**
```java
int i = 1;
while (i <= 5) {
    System.out.println(i);
    i++;
}
```

**Örnek Kod (Do-While Döngüsü):**
```java
int j = 1;
do {
    System.out.println(j);
    j++;
} while (j <= 5);
```

🧑‍🏫 **Açıklama:** `for` döngüsü genellikle belirli sayıda tekrar yapmak için kullanılırken, `while` ve `do-while` döngüleri belirli bir koşul doğru olduğu sürece çalışır.

🎯 **Egzersiz:**
- 1'den 100'e kadar olan tek sayıları bulan bir program yazın.
- Girilen bir sayıya kadar olan tüm sayıların çarpımını bulan bir program yazın.

---

### 3. SwitchExample.java 🔀💡

**Switch yapısı**, bir değişkenin değerine göre farklı kod bloklarını çalıştırmayı sağlar. Çok sayıda if-else yerine daha düzenli bir yapı sunar.

**Örnek Kod:**
```java
int day = 3;
switch (day) {
    case 1:
        System.out.println("Pazartesi");
        break;
    case 2:
        System.out.println("Salı");
        break;
    case 3:
        System.out.println("Çarşamba");
        break;
    default:
        System.out.println("Geçersiz gün!");
}
```

🧑‍🏫 **Açıklama:** Bu örnekte, girilen gün numarasına göre haftanın günlerini yazdıran bir `switch` yapısı kullanıyoruz.

🎯 **Egzersiz:**
- Kullanıcıdan ay numarası alıp hangi mevsimde olduğunu yazdıran bir program geliştirin.
- Bir menü oluşturarak kullanıcının seçimine göre farklı mesajlar veren bir program oluşturun.

---

### 🌟 Genel Egzersizler 🎓
1. **Hesap Makinesi Uygulaması**: Kullanıcıdan iki sayı ve bir işlem türü (toplama, çıkarma, çarpma, bölme) alarak sonucu hesaplayan bir program yazın.
2. **Döngüyle Yıldız Deseni Çizimi**: Kullanıcıdan bir sayı alıp bu sayıya göre ekranda yıldız (*) karakteri ile şekiller çizin. Örneğin, üçgen ya da kare.
