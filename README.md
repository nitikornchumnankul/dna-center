# dna-center
[Diagram](https://app.diagrams.net/#G1htz_zbka45oODL4kBhAl8ijqtznvyS87)
 
[Database Diagram](https://dbdiagram.io/d/5f9d5c2d3a78976d7b79eec0)

[Responsive Design Strategy](https://shaydeecoder.hashnode.dev/responsive-design-strategy-ckglskkmd087pnzs13xfhf85f)

[Flutter Web : Responsive Landing Page - Speed Code](https://www.youtube.com/watch?v=87cz-ihAJ-8&list=RDCMUC9dwxEAvy-zCMAS7rdox46w&start_radio=1&t=5)

# แบบฟอร์ม
รายละเอียดสำหรับการลงทะเบียน
1.	ชื่อสมาชิก...................................  นามสกุล............................................
2.	ชื่อฟาร์ม.......................................จำนวนวัว............................................
3.	ที่อยู่........................................................................................................
4.	เบอร์ติดต่อ..............................................................................................
5.	อีเมลล์.....................................................................................................
6.	Line………………………………………………………………………………………

ข้อมูลตัวอย่างจากวัวที่จะส่งตรวจ

1.	ชื่อวัว/ รหัสวัว...................................เพศ.............................
2.	ประเภทตัวอย่างที่ส่งตรวจ (เลือด/ขนหาง)....................................................
3.	ปริมาณตัวอย่างที่ส่งตรวจ.........................................................................
4.	พ่อพันธุ์............................................................
5.	แม่พันธุ์............................................................

### สร้างหน้า DataCenter
```
flutter create DataCenter
```
### เปิดช่องพัฒนาในรูปแบบเว็บแอปพลิเคชั่น
```
flutter channel beta
```
### อัพเดต flutter
```
flutter upgrade
```
### ตั้งค่าในรูปแบบเว็บแอปพลิเคชั่น
```
flutter config --enable-web
```
### local web application 
```
flutter run -d web --web-port=8080
```
### Using DevTools with a command-line app
1. Install DevTools
```
flutter pub global activate devtools
```
2. Launch the DevTools server
```
flutter pub global run devtools
```
### [Flutter & Chrome OS tips & tricks](https://flutter.dev/docs/get-started/install/chromeos)
```
 flutter pub global run devtools -p 8000
 cd path/to/your/app
 flutter run --observatory-port=8080
```

### Build
```
flutter build web
```
### Add web support to an existing app
```
flutter create .
```

## References

