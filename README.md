# Java SE Shape Örneği

Arayüz (interface) ve onu uygulayan sınıf kavramını göstermek için yazılmış çok küçük bir Java SE örneği.

> **Not:** Bu depo 2015 yılında eğitim amaçlı yazıldı ve artık güncellenmiyor.

## İçerik

| Dosya | Ne yapar |
|---|---|
| `src/com/mustafaergan/interfaces/IShape.java` | `draw()` ve `calc()` metotlarını tanımlayan arayüz |
| `src/com/mustafaergan/drawing/Shape.java` | `IShape` arayüzünü uygulayan sınıf; metot gövdeleri boş, yalnızca iskelet |

Projede `main` metodu yoktur; çalıştırılacak bir uygulama değil, arayüz kullanımını gösteren bir iskelettir.

## Teknolojiler

- Java 8 (Java SE 1.8), harici bağımlılık yok

## Çalıştırma

Eclipse ya da IntelliJ IDEA'da `src` klasörünü kaynak klasör olarak gösteren yeni bir Java projesi açın
ya da komut satırından derleyin:

```bash
javac -d bin src/com/mustafaergan/interfaces/IShape.java src/com/mustafaergan/drawing/Shape.java
```
