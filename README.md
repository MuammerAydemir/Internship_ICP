# Internship_ICP

Merhaba ben **Muammer Aydemir**, yeni bir Bilgisayar Mühendisliği mezun durumundayım ve arka uç geliştirme konusundaki deneyimimle karmaşık problemler ve algoritmalara yaratıcı çözümler bulmaya odaklanıyorum. Teknoloji ve yazılım geliştirme konusundaki tutkum, beni sürekli olarak yeni zorluklarla karşılaşmak ve bu zorlukları çözmek için motive ediyor. Özellikle veri tabanı yönetimi, API tasarımı, **web3** ve performans optimizasyonu gibi alanlarda uzmanlaşmayı hedefliyorum. Bu projede _[2025 Patika.dev Stajı](https://cohorts.patika.dev/cohort-details/2025-patikadev-staji)_ için bir örnektir . :rocket:

**Motogo**, iletişim ve veri yönetimi üzerine kurulmuş basit ve etkili bir backend sistemidir. Bu proje, veritabanı yönetimi, API tasarımı ve performans optimizasyonu gibi temel arka uç geliştirme konularında deneyim kazanmaya yönelik geliştirilmiştir. Proje, kullanıcıların iletişim bilgilerini ve mesajlarını yönetmelerine olanak tanır.

---

## Proje Özeti

**Motogo** ile kullanıcılar, telefon numarası ve mesajları gibi temel iletişim verilerini kolayca ekleyebilir ve sorgulayabilir. Ayrıca, kullanıcılar arasındaki mesajlaşmaları takip etmek için API'ler sunulmaktadır. Bu proje, arka uç geliştirme, veri yönetimi ve API tasarımı konularında sağladığı pratikle özellikle backend mühendisliği alanında kendini geliştirmek isteyenler için yararlıdır.

---

## Ana Özellikler

- **Veri Ekleme (insert)**: Kullanıcı adı ve iletişim bilgilerini içeren yeni bir kayıt ekleyin.
  
- **Veri Sorgulama (getPhone)**: Kullanıcı adıyla ilişkili telefon numarasını sorgulayın.

- **Mesaj Gönderme (sendMessage)**: Bir kullanıcıya mesaj göndermek kullanın.

- **Mesaj Sorgulama (getMessage)**: Bir kullanıcının aldığı mesajları sorgulayın.

---

## Kullanım Örnekleri

### 1. **insert()** - Yeni Kayıt Ekleme

Bir kullanıcı eklemek için şu şekilde kullanabilirsiniz:

```python
insert("Adam", record {desc="Seven deadly sins"; phone="+905123456789"})
```
### 2. **sendMessage()** - Kullanıcıya Mesaj Gönderme

Bir kullanıcıya mesaj göndermek kullanabilirsiniz:

```python
sendMessage() : sendMessage("+905123456789", record {mess="hi!"; receiver="+905987654321"})
```
### 3. **getPhone()** - Yeni Kayıt Ekleme

Kullanıcı adıyla ilişkili telefon numarasını sorgulayabilirsiniz:

```python
getPhone("Adam") : (opt record {desc="Seven deadly sins"; phone="+905123456789"})
```
### 4. **getMessage()** - Yeni Kayıt Ekleme

Bir kullanıcının aldığı mesajları sorgulayabilirsiniz:

```python
getMessage("+905123456789") (opt record {mess="hi!"; receiver="+905987654321"})
```
