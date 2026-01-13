# 🛠️ T-Embed Customizations by E63

Hoş geldiniz! Ben **E63**. Bu repo, Lilygo T-Embed CC1101 Plus cihazım için geliştirdiğim özel projeleri, temaları ve teknik detayları içerir.
Welcome! I am **E63**. This repository contains custom projects, themes, and technical details I developed for my Lilygo T-Embed CC1101 Plus device.

---

## 🎨 My Creations / Çalışmalarım

### 🔴 E63's Red Theme
**TR:** Kendi nick'im olan **E63** adıyla hazırladığım, tamamen bana özel kırmızı ve siyah tonlara sahip kullanıcı arayüzü teması. Görsellik ve fonksiyonelliği bir araya getiren bu tema, T-Embed'in havasını tamamen değiştiriyor.
**EN:** A custom UI theme with red and black tones, created under my nick **E63**. This theme combines aesthetics and functionality to completely transform the T-Embed experience.

### 📽️ Boot.gif
**TR:** Cihaz açılışında beni karşılayan, **E63** imzalı özel açılış animasyonu.
**EN:** A custom boot animation with **E63** signature that greets me when the device starts up.

---

## ⚙️ How to Create Themes for T-Embed? / T-Embed Teması Nasıl Oluşturulur?

<details>
<summary><b>Click to expand / Detayları görmek için tıklayın 📂</b></summary>

### [TR] Adım Adım Tema Oluşturma:
1. **Tasarım:** 320x170 piksel boyutlarında arayüzü tasarlayın.
2. **Renk Paleti:** T-Embed ekranı için RGB565 formatını kullanın.
3. **Dönüştürme:** Görselleri `online image converter` ile .c dosyasına çevirin.
4. **Yükleme:** Dosyaları Firmware koduna ekleyip cihazı flashlayın.

### [EN] Step-by-Step Theme Creation:
1. **Design:** Design the interface at 320x170 pixels.
2. **Color Palette:** Use RGB565 format for the T-Embed screen.
3. **Conversion:** Convert images to .c files using an online image converter.
4. **Flashing:** Include the files in the firmware code and flash the device.
</details>

---

## 🎞️ How to Create a Boot Animation? / Boot Animasyonu Nasıl Yapılır?

<details>
<summary><b>Click to expand / Detayları görmek için tıklayın 📂</b></summary>

### [TR] Boot Dosyası Hazırlama:
1. **GIF Hazırlığı:** 320x170 boyutunda kısa bir animasyon oluşturun.
2. **Format:** Karelerine (frames) ayırın veya doğrudan LVGL formatını kullanın.
3. **Dosya Sistemi:** Hazırladığınız dosyayı LittleFS üzerinden cihaza yükleyin.
4. **Kodlama:** `void setup()` fonksiyonu içinde animasyon kodunu tetiklenen kodu ekleyin.

### [EN] Preparing Boot Files:
1. **GIF Prep:** Create a short animation at 320x170 resolution.
2. **Format:** Split into frames or use the direct LVGL format.
3. **Filesystem:** Upload the file to the device via LittleFS.
4. **Coding:** Trigger the animation code within the `void setup()` function.
</details>

---

**Contact / İletişim:** E63 - [GitHub Profile](https://github.com/e63washere)
