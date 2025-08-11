# 💗 This Song For You My Love (Bam Jeerapa) 💗

เว็บไซต์โรแมนติกสำหรับบอกรักและให้กำลังใจแฟนสาว "แบม" ด้วยเพลงจาก Spotify

## ✨ ฟีเจอร์

- **ข้อความบอกรักสุ่ม**: แสดงข้อความหวาน ๆ เปลี่ยนทุกครั้งที่โหลดหน้าเว็บ
- **Spotify Playlist**: ฝัง Playlist จาก Spotify ให้ฟังเพลงได้ทันที
- **Responsive Design**: รองรับทุกขนาดหน้าจอ (iPhone, iPad, Desktop)
- **ธีมโรแมนติก**: สีหวาน น่ารัก เหมาะกับการบอกรัก

## 🚀 วิธีใช้งาน

### 1. ดาวน์โหลดไฟล์
```bash
git clone https://github.com/opal-Pachara/Song-spotify-Bam.git
cd Song-spotify-Bam
```

### 2. เปิดเว็บไซต์
- เปิดไฟล์ `index.html` ในเบราว์เซอร์
- หรือใช้ Live Server ใน VS Code

### 3. เปลี่ยน Playlist (ถ้าต้องการ)
แก้ไข URL ในไฟล์ `index.html`:
```html
<iframe src="https://open.spotify.com/embed/playlist/YOUR_PLAYLIST_ID?utm_source=generator&theme=0">
```

## 📁 โครงสร้างไฟล์

```
Song-Bam/
├── index.html          # หน้าเว็บหลัก
├── style.css           # ไฟล์ CSS สำหรับดีไซน์
└── README.md           # ไฟล์นี้
```

## 🎨 การปรับแต่ง

### เปลี่ยนข้อความบอกรัก
แก้ไขใน `index.html`:
```javascript
const loveMessages = [
  "ข้อความที่ 1 💖",
  "ข้อความที่ 2 🎶",
  // เพิ่มข้อความตามต้องการ
];
```

### เปลี่ยนธีมสี
แก้ไขใน `style.css`:
```css
body {
  background: linear-gradient(90deg, #สี1 0%, #สี2 100%);
}
```

### เปลี่ยน Playlist
แก้ไข `src` ใน iframe:
```html
<iframe src="https://open.spotify.com/embed/playlist/PLAYLIST_ID">
```

## 📱 Responsive Breakpoints

- **iPhone 11**: ≤ 414px
- **iPad**: 601px - 768px  
- **iPad Pro**: 769px - 1024px
- **Desktop**: ≥ 1025px

## 🎵 Spotify Integration

เว็บไซต์ใช้ Spotify Embed API เพื่อฝัง Playlist โดยไม่ต้องใช้ API Key
- รองรับ Playlist, Album, Artist, Track
- ฟีเจอร์: autoplay, fullscreen, picture-in-picture

## 🌟 เทคโนโลยีที่ใช้

- **HTML5**: โครงสร้างเว็บไซต์
- **CSS3**: การออกแบบและ Responsive Design
- **JavaScript**: ฟังก์ชันสุ่มข้อความและ Interactive
- **Spotify Embed**: ฝังเพลงจาก Spotify

## 💝 ข้อความตัวอย่าง

เว็บไซต์มาพร้อมข้อความบอกรักหลากหลาย:
- "แบม วันนี้เหนื่อยไมคะ ขอให้เพลงเหล่านี้ช่วยเติมพลังใจนะ 💖"
- "รักแบมที่สุดในโลกเลยนะ ฟังเพลงนี้แล้วอย่าลืมคิดถึงเค้าด้วยน้า 🎶"
- "ขอให้เพลงในวันนี้ช่วยให้แบมสดใสในวันรุ่งขึ้นนะคะ 😊"

## 🔧 การพัฒนา

### เพิ่มฟีเจอร์ใหม่
1. แก้ไข `index.html` สำหรับ HTML structure
2. แก้ไข `style.css` สำหรับการออกแบบ
3. เพิ่ม JavaScript functions ใน `<script>` tag

### เพิ่ม Playlist ใหม่
1. คัดลอก Playlist URL จาก Spotify
2. แทนที่ URL ใน iframe src
3. ทดสอบการแสดงผล

## 📄 License

โปรเจกต์นี้สร้างขึ้นเพื่อการใช้งานส่วนตัว

## 💌 ติดต่อ

สร้างด้วย ❤️ สำหรับ "แบม" ที่รัก

---

**หมายเหตุ**: เว็บไซต์นี้ใช้ Spotify Embed ซึ่งไม่ต้องการ API Key และสามารถใช้งานได้ทันที
