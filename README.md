# 🎵 ESP32 Project: Best Friend Song & LCD 0.96"

Proyek simulasi ESP32 untuk memainkan melodi lagu **"Best Friend"** sekaligus menampilkan lirik lagunya secara sinkron pada layar LCD OLED 0.96" (SSD1306).

---

## 🔌 Konfigurasi Pin (Wiring)

Berikut adalah konfigurasi pin yang digunakan antara ESP32 dan Layar OLED 0.96" (I2C):

| Komponen (OLED) | Pin ESP32 | Keterangan |
| :--- | :--- | :--- |
| **SDA** | **21** | Data I2C |
| **SCL** | **22** | Clock I2C |
| **VCC** | **3V3** | Daya 3.3 Volt |
| **GND** | **GND** | Ground |


---

## 🚀 Simulasi Wokwi

Kamu bisa melihat, memodifikasi, dan menjalankan proyek ini secara langsung melalui tautan simulasi Wokwi berikut:

🔗 **[Lihat Project di Wokwi](https://wokwi.com/projects/465501544989612033)**

---

## 🛠️ Library yang Dibutuhkan
Jika kamu ingin mencoba kode ini di Arduino IDE secara offline, pastikan sudah menginstal library berikut melalui *Library Manager*:
1. `Adafruit SSD1306`
2. `Adafruit GFX Library`
