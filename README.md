WARP Config Builder v1.1:

این برنامه به شما کمک میکند تا آیپی و پورتهای خود را به کانفیگ رایج Warp تبدیل کنید.
هر دوفایل را دانلود کرده و از حالت فشرده خارج کنید. روش کار بسیار ساده است، آیپی و پورت را در پنجره سمت چپ paste کنید و با زدن کلید Show result نتیجه را در پنجره سمت راست دریافت کنید.
اگر برای پیدا کردن آیپی پورت تمیز به تعداد زیاد با مشکل مواجه هستید دستور زیر را به ترتیب در ترموکس اجرا کنید:
1: bash <(curl -fsSL https://raw.githubusercontent.com/bin1zone/warp-script-on-ish/main/endip/best_ip_port.sh)
2: cat ip_port.txt

با اجرای فرمان 2 میتوانید محتویات داخل فایل ip_port.txt را مشاهده و آنها را کپی کرده در این نرم افزار استفاده کنید، هر بار که فرمان شماره 1 را اجرا میکنید فایل ip_port.txt در روت main ترموکس ایجاد میشود، برای اینکه با اجرای مجدد دستور شماره یک آیپی و پورت جدید داشته باشید باید فایل ip_port.txt را با این دستور rm ip_port.txt پاک کنید.
##
English description:
This program helps you to convert your IP and ports to the common Warp configuration.
Download and unzip files. The procedure is very simple, paste the IP and port in the left window and press the Show result button to get the result in the right window.
If you are having trouble finding a large number of clean IP and ports, run the following commands in order in Termux:

1: bash <(curl -fsSL https://raw.githubusercontent.com/bin1zone/warp-script-on-ish/main/endip/best_ip_port.sh)
2: cat ip_port.txt

By running command 2, you can view the contents of the ip_port.txt file and copy them and use them in this software, every time you run command number 1, the ip_port.txt file is created in the main root of Thermox. In order to have a new IP and port by running command number one again, you must delete the ip_port.txt file with this "rm ip_port.txt" command.

##
![1111](https://github.com/bin1zone/WARP-Config-Builder/assets/164546270/3f32775d-d82d-4e83-8cc1-b9b24f3849c7)
