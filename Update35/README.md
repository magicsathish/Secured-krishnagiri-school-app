# Digital India – Krishnagiri School App (V3.4.0 Exhibition Master)
## DRM Protected Single-File Web App & Automated Android APK Build

### 🔐 பாதுகாப்பு மற்றும் அணுகல் (DRM Security & Access)
- இந்த அப்ளிகேஷன் **Single-File Self-Locked Container** ஆக வடிவமைக்கப்பட்டுள்ளது.
- யாரும் இந்த `index.html` கோப்பை தனியாக டவுன்லோட் செய்து லோக்கலில் திறந்தாலும், **முதலில் DRM Gatekeeper திரையே தோன்றும்**.
- சரியான பின் எண் (`1234`) உள்ளிட்டால் மட்டுமே உள்ளே இருக்கும் பள்ளி ஆய்வகத் தளம் திறக்கும்.
- **அணுகல் பின் எண் (Default PIN):** `1234`
- **நிர்வாகி பின் எண் (Admin PIN):** `7788`
- கடிகாரத்தைத் பின்னோக்கி மாற்றுதல் (Anti-clock tampering guard) மற்றும் 5 தவறான முயற்சிகளுக்குப் பின் முடக்கும் (Lockout protection) அம்சங்கள் இதில் இணைக்கப்பட்டுள்ளன.

---

### 📱 Android APK தானியங்கி உருவாக்கம் (Automated GitHub Actions APK Build)
இந்த repository-ல் `.github/workflows/build-apk.yml` கோப்பு உள்ளது:
1. இந்த பேக்கேஜில் உள்ள கோப்புகளை உங்கள் `Secured-krishnagiri-school-app` GitHub repository-க்கு push செய்தவுடன், **GitHub Actions தானாகவே இயங்கி Android APK-வை உருவாக்கி விடும்**!
2. உங்கள் GitHub Repository பக்கத்தில் **Actions** டேபிற்குச் சென்றால், உருவான APK-வை நேரடியாக டவுன்லோட் செய்யலாம்.
3. மேலும் **Releases** பக்கத்திலும் `Digital_India_Krishnagiri_V3.4.0_Exhibition_Master.apk` கோப்பு நேரடியாகக் கிடைக்கும்.

---

### 🌐 GitHub Pages நேரலை (Live Hosting)
- Repository Settings ➔ Pages சென்று **Branch: main / root** என அமைத்தால்,
- `https://magicsathish.github.io/Secured-krishnagiri-school-app/` என்ற முகவரியில் நேரலையாக இயங்கும்.
