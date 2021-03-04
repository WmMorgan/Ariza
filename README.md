<p align="center">
    <h1 align="center">Yii 2 Basicda Ish uchun ariza qoldirish applicationi</h1>
    <br>
</p>

<p>
Xatoliklar uchun uzur so'rayman, comment qoldirish mumkin bo'lsa kamchiliklarni yozib qoldirsangiz hursand bo'lardim.

Admin account:
login: admin
parol: morgan

admin login parollarini models/User.php da o'zgartirishingiz mumkin.

<h2>REST API:</h2>
<small>
POST — ariza qoldirish; (api/create)

GET — id beriladi, va shu id dagi nomzod maʼlumotlarini olish; (api/7)

PUT — berilgan id dagi arizani oʻzgartirish; (api/7{json})

DELETE — berilgan id dagi arizani oʻchirib yuborish. (api/7)
</small>
<br><br><br><br><br><br>


PS: 
Agar saytni faqat /web papkasi orqali ishlashini hoxlasangiz script turgan joydagi .htaccess fayliga quyidagi kodni joylang:
<pre>
<IfModule mod_rewrite.c>
    Options +FollowSymlinks
    RewriteEngine On
</IfModule>
<IfModule mod_rewrite.c>
    RewriteRule ^(.*)$ /web [L,R=301]
    RewriteCond %{REQUEST_FILENAME} !-f [OR]
    RewriteCond %{REQUEST_FILENAME} !-d
    RewriteRule ^.*$ web/
</IfModule>
</pre>

Telegram: @C_Morgan</p>