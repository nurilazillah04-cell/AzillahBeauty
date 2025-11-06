<h1 align="center">🌸 Azillah Beauty Website</h1>
<h3 align="center">Website Cloud Cybersecurity Project — Netlify Deployment with HTTPS & SSL</h3>

<p align="center">
  <a href="https://sensational-stardust-d875bf.netlify.app/">
    <img src="https://img.shields.io/badge/Status-Deployed-success?style=for-the-badge&logo=netlify" alt="Deployment Status">
  </a>
  <a href="https://github.com/nurilazillah04-cell/AzillahBeauty">
    <img src="https://img.shields.io/badge/Repo-GitHub-blue?style=for-the-badge&logo=github" alt="GitHub Repo">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/SSL-Secure-green?style=for-the-badge&logo=letsencrypt" alt="SSL Secure">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/License-Academic-blueviolet?style=for-the-badge" alt="License">
  </a>
</p>

---

## 📘 Deskripsi Proyek  
Proyek **Azillah Beauty** merupakan studi kasus penerapan **Cloud Cybersecurity** berbasis *website statis* yang dihosting di **Netlify**.  
Website ini menampilkan produk skincare lokal dan dirancang untuk menunjukkan penerapan **keamanan cloud** menggunakan **HTTPS (SSL/TLS)** secara otomatis dengan sertifikat **Let’s Encrypt**.  

Tujuan proyek ini adalah melatih kemampuan mahasiswa dalam:
- Mengimplementasikan hosting cloud dengan *security layer*.
- Menerapkan *version control system* melalui GitHub.
- Menganalisis performa dan keamanan website berbasis cloud.
- Menyusun laporan teknis berbasis hasil implementasi nyata.

---

## 🎯 Tujuan Akademik  
1. Menunjukkan pemahaman praktis konsep keamanan cloud.  
2. Menerapkan sistem *deployment* dengan keamanan terintegrasi.  
3. Menguji performa dan *compliance* situs melalui alat evaluasi otomatis.  
4. Menghasilkan laporan dan dokumentasi proyek profesional berbasis cloud.

---

## 🧩 Struktur Folder Proyek  


---

## ☁️ Platform & Tools  

| Komponen | Teknologi / Layanan |
|-----------|---------------------|
| Cloud Hosting | [Netlify](https://www.netlify.com/) |
| SSL Certificate | Let’s Encrypt (otomatis via Netlify) |
| Version Control | [GitHub](https://github.com/nurilazillah04-cell/AzillahBeauty) |
| Bahasa | HTML5, CSS3 |
| Testing Tools | Google Lighthouse, SSL Labs, SSL Checker |
| Desain Visual | SVG & CSS |
| Pengujian Browser | Chrome, Edge, Firefox |

---

## ⚙️ Langkah Implementasi  

### **1️⃣ Persiapan Folder Proyek**
Semua file dibuat dan diatur dengan struktur berikut agar mudah dikelola dan di-*deploy*:


---

### **2️⃣ Deployment ke Netlify**
1. Buka halaman: [https://app.netlify.com/drop](https://app.netlify.com/drop)  
2. Seret folder proyek ke area upload.  
3. Tunggu hingga proses *deploy* selesai.  
4. Situs aktif otomatis di domain:  
   🔗 **https://sensational-stardust-d875bf.netlify.app/**  
5. HTTPS otomatis aktif melalui **Let’s Encrypt SSL**.  

---

### **3️⃣ Verifikasi HTTPS**
- Akses situs via Edge / Firefox dan pastikan ikon gembok 🔒 muncul.  
- Klik gembok → pastikan tertulis “Connection is secure”.  
- Uji sertifikat via **[SSL Labs](https://www.ssllabs.com/ssltest/)** → hasil: **Grade A (Excellent)**.

---

### **4️⃣ Pengujian Performa**
Gunakan **Google Lighthouse (DevTools)** untuk mengukur:
- Performance  
- Accessibility  
- Best Practices  
- SEO  

📊 **Hasil Pengujian:**
| Aspek | Skor |
|--------|------|
| Performance | 92% |
| Accessibility | 90% |
| Best Practices | 95% |
| SEO | 91% |
| Waktu Muat | 1.8 detik |
| SSL Grade | A |

---

## 🔐 Konfigurasi Keamanan  
| Jenis Proteksi | Deskripsi |
|----------------|------------|
| **HTTPS (SSL/TLS)** | Melindungi komunikasi data antara client–server. |
| **CDN + Edge Network** | Menyebarkan konten dari lokasi terdekat pengguna untuk kecepatan & keamanan. |
| **Automatic Backup** | Netlify menyimpan versi situs sebelumnya untuk rollback cepat. |
| **Web Application Firewall (WAF)** | Mendeteksi dan mencegah serangan umum (XSS, DDoS, Injection). |
| **SSL Renewal Automation** | Sertifikat diperbarui otomatis setiap 90 hari. |

---

## 🧠 Arsitektur Sistem  


### 🧭 Diagram Arsitektur Cloud
<p align="center">
  <img src="https://raw.githubusercontent.com/nurilazillah04-cell/AzillahBeauty/refs/heads/main/Diagram%20AzillahBeauty%20Website.png" 
       alt="Diagram Arsitektur Cloud Azillah Beauty" width="600">
</p>


---

## ⚠️ Analisis Risiko & Mitigasi  
| Risiko | Dampak | Strategi Mitigasi |
|--------|---------|-------------------|
| DDoS Attack | Situs lambat/tidak dapat diakses | Proteksi CDN dan Edge Firewall |
| SSL Expired | Situs tidak aman | Perpanjangan otomatis Let’s Encrypt |
| Human Error Deploy | File salah versi | Version control GitHub & rollback Netlify |
| Modifikasi ilegal | Konten berubah | Sistem autentikasi GitHub (commit history) |

---

## 📈 Evaluasi Akhir
Website **Azillah Beauty** berhasil dideploy dengan aman, cepat, dan konsisten.  
Proyek ini menunjukkan pemahaman nyata tentang:
- *Cloud deployment pipeline*  
- *Secure web hosting (SSL/TLS)*  
- *Performance optimization*  
- *Risk management & backup system*

---

## 👩‍💻 Identitas Pengembang  

| Keterangan | Data |
|-------------|------|
| **Nama** | Nuril Azillah |
| **NIM** | 230170135 |
| **Program Studi** | Teknik Informatika |
| **Universitas** | Malikussaleh |
| **Tahun** | 2025 |

---

## 📚 Lisensi & Hak Cipta  
Proyek ini dikembangkan untuk keperluan akademik dan pembelajaran.  
Segala bentuk konten bersifat **non-komersial** dan digunakan untuk mendemonstrasikan penerapan **keamanan cloud pada website statis**.

---

<h4 align="center">🔒 “Security is not a feature — it’s a foundation.”</h4>  
<p align="center">
  Developed by <b>Nuril Azillah</b><br>
  🌐 <a href="https://sensational-stardust-d875bf.netlify.app/">Visit Project Website</a>
</p>

