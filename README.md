## Proje Adı: Oyun Kütüphanesi
<br>

### Proje Ekibi : Sıray TARIM, Sevgi PEKİN, Ahmet Salih DOĞAN
<br>


### Proje Gereksinimleri:
<br>

- Kullanıcı olabilmek için mail ve şifre gerekir. 

- Bir kullanıcı bir hesaba giriş yapabilir. 

- Mail onayından sonra bir kullanıcı için bir id belirlenir. 

- Platformda birden çok kullanıcı olabilir. 

- Bir oyuncu birden çok oyuna sahip olabilir. 

- Bir oyunun birçok kullanıcısı olabilir. 

- Bir oyunun bir geliştiricisi olabilir. 

- Bir geliştiricinin birden çok oyunu olabilir. 

- Bir oyunu yayımlayan bir şirket olabilir. 

- Bir şirketin yayımladığı birçok oyun olabilir. 

- Bir kullanıcı bir oyuna geribildirim yapabilir. 

- Platform içindeki oyunlara kategorilerden ulaşılabilir. 

- Her tür birden fazla kategoriye ait olabilir. 

- Türler kısmının içerisinde oyunların türlerine ait genel başlıklar ve onların alt başlıkları bulunur. 

- Türler kendi içlerinde birkaç alt başlığa ayrılabilir. (Aksiyon, Arcade, Rol Yapma, Birinci Şahıs Nişancı vb.) 

- Oyunların sağladığı işletim sistemleri için de macOS, Steam OS + Linux için bulunur. 

- Oyunlar; oyun id, oyun adı, türü, fiyatı, çıkış tarihi, yazılımcısı, yayımcısı, sağlandığı sistemler, geri bildirimi gibi bilgilere sahiptir. 


<br>

### İlişkisel Şema:   
<br>

**Users**
- u_id: int
- u_Name: varchar
- u_date: datetime
- u_SiteLink: varchar
- u_username: varchar
- u_ProfilePic: varchar
- u_about: varchar
- u_Age: int
  
<br>

**Kullanıcı Girişi**
- u_username: varchar
- u_password: varchar

<br>

**Kullanıcı Kaydı**
- u_mail: varchar
- u_password: varchar

<br>

**Games**
- g_id: int
- g_Name: varchar
- g_ReleaseTime: datetime
- g_Dev: varchar
- g_Pub: varchar
- g_Type: varchar
- g_Price: smallmoney
- g_OS: varchar
- g_review: int
- g_tags: varchar
- g_Desc: varchar

<br>

**Kategoriler**
- ca_name: varchar

<br>

**Türler**
- t_id: int
- t_name: varchar

<br>

**Reviews**
- r_id: int
- r_comment: varchar
- r_votes: int

<br>

**Publisher**
- p_id: int
- p_name: varchar

<br>

**Developer**
- d_name: varchar

<br>

## E-R Diyagramı :
<br>

![210260060_210260100_210260020_Oyun_Kütüphanesi 2 -page-001](https://github.com/user-attachments/assets/1033a5e8-5c7f-4d66-a9f9-9ac80e248b95)






  


