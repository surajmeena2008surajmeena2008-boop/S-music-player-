# S Music Player 0.0.5

## 0.0.5 mein naya
- Upar kone mein gear ki jagah app ka icon (tap karne par install help).
- Phone rotate karne par landscape interface: left mein album art, right mein search / add / Speed pills, song name, heart, seek bar aur controls. Sab kuch kaam karta hai.
- Album art na ho to headphones dikhte hain.
- search 🔍: songs ki list kholta hai, type karne par filter hota hai, song par tap karne par bajta hai.
- add 📥: folder (ya songs multi-select) chunne ka option.
- Speed 🐎: Slowed aur Pitch wala panel.
- Theme song ke album art ke hisaab se badalti hai (portrait aur landscape dono mein: background, card, pills, speed bar). Art na ho to purani black/maroon theme.
- Play button ab sirf play/pause karta hai (file picker nahi kholta).
- Dono layouts (portrait + landscape) ab song ke album art ke rang ke hisaab se adaptive theme lete hain; art na ho to default theme.
- Landscape mein album art ~4×4 cm (250px) ka, aur chhoti screen par fit hone ke liye apne aap chhota hota hai (size badalna ho to index.html mein `--art`).

## GitHub par upload (zaroori)
ZIP extract karke **andar ki saari 9 files (index.html, manifest.json, sw.js aur 6 png icons)** repo mein usi jagah upload karein jahan purani `index.html` hai: ek saath select karke (folder ki zaroorat nahi, sab files seedhi repo mein). Sirf `index.html` badalne se install/icon theek nahi hoga.
Commit ke baad purani installed app delete karein, Chrome mein site data clear karein, page do baar refresh karein, phir ⋮ → **Install app**.
