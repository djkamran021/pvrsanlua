💻آموزش :💻
🎈ابتدا فایل را اکسترکت کرده و وارد پوشه شوید سپس فایل config.lua را باز کنید و بجای متن (توکن شما) توکن بات پیام رسان خود را جایگزین کنید و در خط پایین جلوی admins آیدی عددی خودتان را جایگزین کنید سپس به پوشه plugins رفته و فایل Contactus.lua را باز کنید و دنبال متن زیر بگردید :🎈
api.forwardMessage 
بجای -139110802 آیدی عددی گروه که میخواید بات پیام هارا به آنجا فروارد کند بنویسید یادتان باشد - را از اول آیدی برندارید سپس دوباره سرچ را باز کرده و دنبال متن زیر نیز بگردید :
msg.chat.id == -139110802
📌و در اینجا نیز مثل بالا آیدی عددی گروه مورد نظر را جایگزین کنید و نکته بالا را رعایت کنید
👇سپس سیو کنید و وارد وی پی اس خود شده و پوشه PmRsn را در وی پی اس خود کپی کنید بعد از آن دستورات زیر را در ترمینال وارد کنید :👇
wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz 
 tar zxpf luarocks-2.2.2.tar.gz 
cd luarocks-2.2.2 
 ./configure; sudo make bootstrap 
 sudo luarocks install luasocket
 sudo luarocks install luasec 
sudo luarocks install redis-lua 
 sudo luarocks install lua-term
 sudo luarocks install serpent 
cd .. 
sudo service redis-server start
🚀وقتی که تمام شد با دستور cd وارد پوشه بات شوید و بنویسید ./launch.sh تا بات پیام رسان شروع به کار کند میتوانید برای ران کردن داعمی از دستور nohup ./launch.sh نیز استفاده کنید🚀

🖊 آموزش توسط : @kamranya ✒️

🔨 بات و پلاگین ها فارسی شده توسط تیم سودو 🔨

❤️ با تشکر ❤️

😘 کپی فقط با ذکر منبع 😘
