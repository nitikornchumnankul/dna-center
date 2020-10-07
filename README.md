# dna-center
[Diagram](https://app.diagrams.net/#G1htz_zbka45oODL4kBhAl8ijqtznvyS87)

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

