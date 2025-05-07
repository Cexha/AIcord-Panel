AIcord Panel

> Yapay Zekâ destekli gelişmiş Discord moderasyon botu ve web paneli.

**AIcord Panel**, sunucunu spam, küfür, toksik davranış gibi tehditlerden korumak için özel olarak geliştirilmiş bir Discord moderasyon sistemidir. Hem gelişmiş komutlara sahip bir Discord botu, hem de verileri görselleştiren şık bir web panel içerir.

![AIcord Banner](https://media.discordapp.net/attachments/1342577482913808516/1368314143089758270/IMG_1109.png?ex=681c6299&is=681b1119&hm=c1c2d7f9be44871d7b952c6d9cc1dac5da17b0007eebcad1359298e5de499589&)

## Özellikler

- ✅ Yapay zekâ ile mesaj analizi (toxicity, spam, küfür tespiti)
- ✅ Web panel üzerinden kullanıcı geçmişi ve analizler
- ✅ Otomatik uyarı ve ceza sistemi
- ✅ Rol yönetimi, mesaj temizleme, kullanıcı takip sistemi
- ✅ Gerçek zamanlı Socket.IO ile panel güncellemeleri
- ✅ Tailwind destekli mobil uyumlu kullanıcı arayüzü

---

## Teknolojiler

- **Discord.js v14**
- **Node.js**
- **Express.js**
- **Socket.IO**
- **MongoDB**
- **OpenAI API**
- **Tailwind CSS**
- **React.js / Vite**

---

## Kurulum

```bash
git clone https://github.com/cexha/aicord-panel.git
cd aicord-panel
npm install
```

### .env dosyasını oluştur:

```env
DISCORD_TOKEN=bot-token
MONGO_URI=mongodb-bağlantı
OPENAI_KEY=openai-api-anahtarın
PANEL_PASSWORD=senin-admin-şifren
```

### Botu Başlat

```bash
cd bot
node index.js
```

### Web Paneli Başlat

```bash
cd panel
npm install
npm run dev
```

---

## Ekran Görüntüleri

![Dashboard](https://cdn.discordapp.com/attachments/1342577482913808516/1369614380957958164/A6270935-C128-4612-90A5-FFD0FC52174E.png?ex=681c804a&is=681b2eca&hm=c4ecd3ff61b08e6a89547ce9cd7840aa3cbdd1c15a281fb95bd27709e7b6acc3&)

---

## Katkıda Bulun

Pull request’ler her zaman açıktır. Daha iyi hale getirmek için katkı sağlamak istersen, fork’la ve geliştirmeye başla!

---

## ⚖️ Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.

---

## ❤️ Katkıda Bulun

Pull request’lere her zaman açığız! Yeni özellik fikirlerin varsa [Issues](https://github.com/Cexha/AIcord-Panel/issues) sekmesine yazmayı unutma!

---

## 👑 Geliştirici

**AIcord & SentinelAI** projeleri  
by [@Cexha](https://github.com/Cexha)
