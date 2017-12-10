ระบบพื้นฐานได้รับการ Fork และพัฒนามาจาก:https://github.com/HFenter/MarginBot
ใช้ระบบ PHP เพื่อรัน Margin Lending Management Bot สำหรับ Bitfinex โดยใช้ระบบ API (https://bitfinex.com/pages/api)

## เนื้อหา
ระบบบอท Lending นี้สร้างขึ้นมาเพื่อเป็นระบบจัดการบัญชีสำหรับ bitfinex ซึ้งพัฒนาขึ้นมาให้สามารถทำกำไรจากการ Lending ให้ได้มากที่สุดและรวดเร็วที่สุด.



### การติดตั้ง

1.[ดาวโหลดไฟล์เวอร์ชั่นล่าสุด](https://github.com/aotlunla/BitfinexLendingBot-TH/archive/master.zip)
2.อัพโหลดและ unzip ไฟล์ที่ดาวน์โหลดไปที่เซิฟเวอร์หรือโฮสติ้งของคุณในหน้า Directory ที่ต้องการ (แนะนำให้ใช้ root directory ของโฮสติ้ง) (PHP 5.6 Recommend)
3.เมื่อเข้าสู่เว็บไซต์ระบบจำทำการ redirect ไปที่ "http://yoursite.domain/install.php" จากนั้นให้ทำการติ้ดตั้งตามขั้นตอน



### วิธีการอัพเดตระบบ เมื่อมีการอัพเดตเวอร์ชั่นใหม่

**สำคัญ**  - ให้ทำการ Backup ไฟล์ inc/config.php ก่อนทุกครั้งก่อนอัพเดต!!

1.เพื่ออัพเดตระบบให้ท่านดาวน์โหลดไฟล์เวอร์ชั่นล่าสุดได้ที่ [ดาวโหลดไฟล์เวอร์ชั่นล่าสุด](https://github.com/aotlunla/BitfinexLendingBot-TH/archive/master.zip).
2.ทำการอัพเดตโหลดไฟล์ทั้งหมดไปที่ directory ของท่านโดยเขียนไฟล์ทับทั้งหมด
3.ให้ทำการอัพโหลดไฟล์ config.php ที่ Backup ไว้เขียนทับไฟล์ที่อัพเดตใหม่
4.เมื่อเข้าสู่หน้าเว็บไซต์ระบบจะเรียกท่านไปที่  http://yoursite.domain/update.php โดยอัตโนมัติ **หากระบบไม่ทำการ Redirect โดยอัตโนมัติให้ทำการอัพเดตได้โดยพิมพ์ไปที่ http://yoursite.domain/update.php ได้ด้วยตนเอง



## ความต้องการของระบบ

* เว็บโฮสติ้งหรือเว็บเซิฟเวอร์ที่สามารถใช้งานได้ (ท่านสามารถติดตั้งระบบไปที่ subdomain หรือ sub folder ที่ต้องการได้)
* ระบบ PHP 5.1 - 5.6
* ระบบ MySQL
* ระบบหรือโอสติ้งที่สามารถเพิ่มหรือแก้ไข cronjob ได้
* บัญชี [ฺBitfinex](https://www.bitfinex.com/signup) และ [(API Access)](https://www.bitfinex.com/account/api)
* เงินในบัญชี Bitfiniex ขั้นต่ำ $50 (เป็นขั้นต่ำของการทำ Margin บน Bitfinex หากต่ำกว่านี้ระบบจะไม่สามารถทำ Margin ได้). **จำนวนเงินขั้นต่ำที่แนะนคือ $100.

**หากท่านยังไม่มีบัญชี Bitfinex สามารถสมัครได้โดยคลิ๊กที่ >>> [สมัครสมาชิก Bitfinex](https://www.bitfinex.com/signup) <<<



## โดเนท
เพื่อให้เราพัฒนาระบบนี้อย่างต่อเนื่องท่านสามารถโดเนทมาได้ผ่านทาง 
   * Bitcoin: 3Lng1vuLUVfykYdhCHnLEU133tTQuSqo41
   ![Donate](https://i.imgur.com/vPb8zYF.png)
   
   * True Wallet: 098-557-5045





