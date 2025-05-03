AIcord Panel

> Yapay Zekâ destekli gelişmiş Discord moderasyon botu ve web paneli.

**AIcord Panel**, sunucunu spam, küfür, toksik davranış gibi tehditlerden korumak için özel olarak geliştirilmiş bir Discord moderasyon sistemidir. Hem gelişmiş komutlara sahip bir Discord botu, hem de verileri görselleştiren şık bir web panel içerir.

![AIcord Banner](https://cdn.discordapp.com/attachments/1342577482913808516/1368314143089758270/IMG_1109.png?ex=6817c559&is=681673d9&hm=83074705ccf4658b0e382d1380bd98a8af34e443e3ce04b728df29df089d7d0b&)

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

![Dashboard](Yakında)

---

## Katkıda Bulun

Pull request’ler her zaman açıktır. Daha iyi hale getirmek için katkı sağlamak istersen, fork’la ve geliştirmeye başla!

---

## Lisans

MIT License © [Cexha](https://github.com/Cexha)
