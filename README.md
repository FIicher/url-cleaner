<DIV align="center">
  <img src="https://dihu.fr/appgithub/iconedihu/9.png" width="120" style="border-radius: 20px; margin-bottom: 15px;">
  <H3>🔗 URL Cleaner</H3>
  <h4>Supprime instantanément les paramètres de tracking (UTM, FBCLID, GCLID...)</h4>
  <h4>Instantly removes tracking parameters (UTM, FBCLID, GCLID...)</h4>
</DIV>

<b>À propos / About :</b><br>
<i>Les liens partagés sur le web contiennent très souvent des paramètres de tracking qui polluent l’URL. Cet outil les retire automatiquement, pour un partage plus propre, plus court, et plus respectueux de la vie privée.<br>
Most shared links contain tracking parameters that make URLs longer and leak marketing data. This tool instantly cleans them, producing cleaner, shorter, privacy-friendly links.</i><br><br>

<b>Fonctionnement / How it works :</b><br>
1- <i>Coller votre URL / Paste your URL<br></i>
2- <i>Cliquer sur “Nettoyer l’URL” / Click “Clean URL”<br></i>
3- <i>Récupérer l’URL propre / Copy your cleaned link<br></i>
4- <i>Tout est 100% local, aucune donnée envoyée / Everything runs 100% locally — your data never leaves your browser<br><br></i>

<b>Installation via NPM / NPM Install :</b><br>
<i>Vous pouvez maintenant utiliser URL Cleaner directement dans vos projets Node.js :</i><br>
<pre>
npm install url-cleaner-fiicher
</pre>
<i>Then in your project / Ensuite dans votre projet :</i><br>
<pre>
const { cleanURL } = require("url-cleaner-fiicher");

const url = "https://example.com/?utm_source=google&utm_medium=cpc&fbclid=12345";
console.log(cleanURL(url));
// → https://example.com/
</pre><br>

<b>Technologies utilisées / Technologies used :</b><br>
<i>- HTML + Vanilla JavaScript<br>
- TailwindCSS (CDN)<br>
- Font Awesome (CDN)<br><br></i>

---

<DIV align="center">
![BadgeCustom](https://img.shields.io/badge/URL--Cleaner-OpenSource%20%E2%9C%85-blue?style=for-the-badge)
![BadgeClean](https://img.shields.io/badge/Tracking%20Removed-%F0%9F%94%97%20Clean%20Links-0B8FEA?style=for-the-badge)

<h5>Partage propre. Vie privée respectée. Navigue léger 🧹 / Share clean. Keep privacy. Browse lighter 🧹</h5>
</DIV>
