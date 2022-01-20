# Google reCAPTCHA admin area OC 2-3

This mod allows to add Google reCAPTCHA admin login page.
Opencart versions : 2.x - 3.x

The real benefits of this mod:
IT BLOCK all database query until Captcha became walid!

(Default opencart controller every login attempt call $this->user->login() method...
So if a BOT trie to login fast as lightning , it can generate many DB query in a second,
and your store databse can slow down , or stop working!)

#Install instructions 

Video instructions here: https://www.youtube.com/watch?v=evkpQrY5ypc

ocmod installer

Setting:
You need to login Google v3 Admin Console
Generate reCAPTCHA v2 - "I'm not a robot" Checkbox type
(IMPORTANT it will work only this type!!)

After you get your site key and secret key
go to admin extension->extension->Captcha
and set up Google reCAPTCHA.

Finished.. 
module starts working, enjoy it .. :)

If you can't login into your admin area!!!
Locate your storage/modification/admin folder and delete it!
(Sotorage folder locaion in your config.php)
