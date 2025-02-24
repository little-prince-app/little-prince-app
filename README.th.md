
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/little-prince-app/little-prince-app/blob/main/README.md)

# Little Prince 👋
Little Prince คือ แอปพลิเคชันที่เก็บภาพยนตร์ผู้ใหญ่ที่คุณชื่นชอบในฐานข้อมูลและช่วยซิงค์กับที่เก็บข้อมูลของคุณ

![Movie View](files/image_jav_landing_page.png)
_Little Prince home_

## ความต้องการ
Little Prince เป็นแอปพลิเคชันเดสก์ท็อปที่รองรับทั้ง Windows และ MacOS (เร็วๆ นี้) รองรับ Windows 10 หรือใหม่กว่า หรือ MacOS 10.14 ขึ้นไป  [ตรวจสอบเวอร์ชันใหม่ได้ที่นี่](https://github.com/little-prince-app/little-prince-app/releases).

## คุณสมบัติ
* ซิงค์ข้อมูลจากไฟล์ meta.json ในที่จัดเก็บ
* นำเข้าข้อมูลภาพยนตร์ไปยังฐานข้อมูลจาก รหัส JAV
* แสดงรายการและรายละเอียดภาพยนตร์
* จัดเรียงข้อมูลภาพยนตร์ตามเรตติ้ง วันที่ออกฉาย และจำนวนนักแสดงหญิง
* จัดเรียงนักแสดงหญิงตามชื่อ เรตติ้ง ขนาดหน้าอก และส่วนสูง
* ค้นหาภาพยนตร์จากรหัส ชื่อภาพยนตร์ ประเภท และชื่อนักแสดงหญิง
* รองรับการให้คะแนนของผู้ใช้สำหรับภาพยนตร์และนักแสดงหญิงที่ชื่นชอบ
* ดาวน์โหลดข้อมูลพื้นฐานของภาพยนตร์ เช่น ชื่อ นักแสดง และประเภท
* ดาวน์โหลดรูปภาพของนักแสดงหญิง
* ดาวน์โหลดภาพหน้าจอภาพยนตร์
* จัดกลุ่มข้อมูลภาพยนตร์ตามประเภท
* จัดกลุ่มข้อมูลภาพยนตร์ตามผู้สร้าง
* จัดกลุ่มข้อมูลภาพยนตร์ตามคำนำหน้าโค้ดและรายละเอียดเกี่ยวกับขนาดไฟล์
* และอื่นๆ ...

## ภาพรวม

Little Prince ช่วยเก็บข้อมูลในฐานข้อมูลภาพยนตร์ของคุณ ทำให้คุณสามารถค้นหาและกรองตามชื่อ ประเภท นักแสดง และอื่นๆ ได้อย่างง่ายดาย นอกจากนี้ ยังสามารถจัดเรียงตามชื่อ รหัสภาพยนตร์ นักแสดง วันที่ออกฉาย และเรตติ้งของคุณเองได้อีกด้วย

![Movie View](files/image_jav_movie_gridview.png)
_Little Prince movie viewer_

เมื่อคุณคลิกที่ภาพยนตร์ในรายการภาพยนตร์ แอปจะแสดงรายละเอียดภาพยนตร์ รวมถึงชื่อภาพยนตร์ ปก ประเภท นักแสดง ภาพหน้าจอ และข้อมูลทั้งหมดที่เกี่ยวข้อง

![Movie View](files/image_jav_movie_detail_view.png)
_Little Prince movie detail page_

คุณสามารถปรับแต่งข้อมูลตามที่ต้องการหรือให้แอปดาวน์โหลดข้อมูลจากอินเทอร์เน็ตได้เช่นกัน

![Movie View](files/image_jav_movie_detail_view_form.png)
_Little Prince movie detail_

สามารถเลือกดูรายการภาพยนต์จากมุมมอง List ก็ได้เช่นกัน 

![Movie View](files/image_jav_movie_list_view.png)
_Little Prince movie_

มุมมองรายละเอียด หากต้องการดูข้อมูลแบบละเอียดจำนวนมาก

![Movie View](files/image_jav_movie_list_detail_view.png)
_Little Prince movie_

## นักแสดง

คุณสามารถเพิ่มนักแสดงที่คุณชื่นชอบได้ กำหนดได้ทั้งชื่อ cup รูปภาพ และสามารถเลือกการจัดเรียงและกรองข้อมูลได้

![Movie View](files/image_jav_actress_view.png)
_Little Prince actress viewer_

เมื่อคลิกที่รูปภาพนักแสดงหญิง จะแสดงหน้ารายละเอียดต่างๆ และภาพยนตร์ที่เกี่ยวข้อง คุณสามารถปรับแต่งข้อมูลตามที่ต้องการหรือให้แอปดาวน์โหลดข้อมูลจากอินเทอร์เน็ตได้เช่นกัน

![Movie View](files/image_jav_actress_detail_view.png)
_Little Prince actress detail_

## ซิงค์ไปยังฐานข้อมูล

คุณจำเป็นต้องกำหนดที่จัดเก็บไฟล์ข้อมูลก่อนที่เมนูฐานข้อมูล หากคุณมีไฟล์วิดีโอหรือไฟล์รูปภาพ จำเป็นต้องเก็บในรูปแบบที่กำหนดตามโครงสร้าง จากนั้นคุณสามารถซิงค์ข้อมูลมายังฐานข้อมูลได้

![Jav database](files/image_jav_database_page.png)
_Database pgae_


## โครงสร้างโฟลเดอร์

ข้อมูลเกี่ยวกับโครงสร้างการจัดเก็บไฟล์ จำเป้นต้องระบุที่อยู่ของโฟลเดอร์ คุณสามารถทำได้ในเมนู Database ตัวอย่างเช่น N:\LITTLE_PRINCE

ข้อมูลในโฟลเดอร์จะประกอบไปด้วยไฟล์ต่างๆ
ตัวอย่างสำหรับ GVG-343

```
LITTLE_PRINCE
    │
    └─JAV
        ├─movies
        │    └─GVG
        │        │  
        │        ├─GVG-343
        │        │    │  GVG-343.jpg
        │             │  GVG-343.mp4
        │             │  feature.jpg
        │             │  meta.json
        │             ├─ screenshots 
        │                       └─  ...
        │
        │
        └─actresses
            ├─EIMI_FUKADA
            │   │  main.jpg
            │   
            ├─SUZU_HONJO
            │   │  main.jpg
```

![Example](files/image_jav_example_file.png)

_Example of GVG-343 in JAV/movies/GVG/GVG-343_

## ข้อมูลภาพยนตร์ JAV

ข้อมูลของภาพยนตร์จะถูกเก็บไว้ในไฟล์ชื่อ meta.json ซึ่งจะเก็บไว้ในโฟลเดอสำหรับรหัสภาพยนตร์แต่ละเรื่อง

ตัวอย่างข้อมูลภายในไฟล์ meta.json
N:\LITTLE_PRINCE\JAV\movies\GVG\GVG-343\meta.json

```
{
    "code": "GVG-343",
    "content_id": "gvg00343",
    "release_date": "2016-08-03",
    "duration_minute": null,
    "director": "Sean Saito",
    "maker": "Glory Quest",
    "series": null,
    "genres": [
        "BIG TITS",
        "OUTDOOR",
        "THREESOME / FOURSOME"
    ],
    "rating": 3,
    "movie_title": "Big-Titted Masochistic Women Dumped Naked In Woods",
    "movie_title_custom": "Bondage 4 Big-Titted",
    "story": null,
    "note": null,
    "count_actress": 4,
    "actresses": [
        "MIKAN KURURUGI",
        "MINAMI AYASE",
        "MION HAZUKI",
        "SERINA FUKAMI"
    ],
    "scenes": [],
    "has_subtitle_file": false,
    "has_climax_gif": false,
    "has_preview": false
}
```

## ข้อมูลนักแสดง

ข้อมูลของนักแสดงจะถูกเก็บไว้ในไฟล์ชื่อ meta.json ซึ่งจะถูกเก็บไว้ในโฟลเดอร์แยกกันสำหรับชื่อนักแสดงแต่ละคน

ตัวอย่างข้อมูลภายในไฟล์ meta.json
N:\LITTLE_PRINCE\JAV\actresses\EIMI_FUKADA\meta.json

```
{
    "name": "EIMI FUKADA",
    "name_other": null,
    "birth_day": "1998-03-18T00:00:00.000",
    "debut_date": "2018-11-03T00:00:00.000",
    "cup": "H",
    "height": 159,
    "rating": 3
}
```

## เครื่องมือ

แอปมีเครื่องมือที่ช่วยให้คุณนำเข้าและดาวน์โหลดข้อมูลได้อย่างรวดเร็ว
* นำเข้าภาพยนตร์ด้วย code
* ดาวน์โหลดปกภาพยนตร์
* ดาวน์โหลดข้อมูลของภาพยนตร์
* นำเข้านักแสดงพร้อมชื่อ
* ดาวน์โหลดรูปภาพนักแสดง
* ดาวน์โหลดข้อมูลของนักแสดง

![jav tool](files/image_jav_tool.png)
_Little Prince jav tools_


ตัวอย่างการเพิ่มรหัสหนังได้หลายเรื่องในคราวเดียว

![Importing movie](files/image_jav_importing_movie_page.png)
_Little Prince adding movie_

ตัวอย่างตัวช่วยการดาวน์โหลดภาพหน้าปก

![Downlaoding cover](files/image_jav_download_movie_cover_page.png)
_Little Prince downloading movie cover_


ตัวอย่างตัวช่วยการดาวน์โหลดข้อมูลของภาพยนตร์ (metadata)

![alt text](files/image_jav_download_movie_metadata_page.png)

## สนับสนุนเรา

[เลี้ยงกาแฟผู้พัฒนา](https://buymeacoffee.com/little.prince)