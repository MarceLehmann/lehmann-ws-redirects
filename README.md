# lehmann.ws → powerplatformtip.com Redirects

## 🎯 GitHub Pages Setup für 301 Redirects

Dieser Ordner enthält alle Dateien für GitHub Pages, um lehmann.ws zu powerplatformtip.com umzuleiten.

### 📁 Struktur:
- `_config.yml` - Jekyll Konfiguration
- `Gemfile` - Ruby Dependencies  
- `CNAME` - Domain Setup
- `robots.txt` - SEO Einstellungen
- `index.html` - Homepage Redirect
- `create_all_redirects.py` - Script für alle 30 Redirects
- `/[url-pfad]/index.html` - Individual Redirects

### 🚀 Setup Schritte:

1. **GitHub Repository erstellen**
   - Neues Repository: `lehmann-ws-redirects`
   - Alle Dateien uploaden

2. **GitHub Pages aktivieren**
   - Settings → Pages
   - Source: Deploy from branch
   - Branch: main / (root)

3. **Domain konfigurieren**
   - Custom domain: `lehmann.ws`
   - DNS bei Provider: CNAME → [username].github.io

4. **SSL aktivieren**
   - "Enforce HTTPS" anklicken

### 🔧 Alle Redirects generieren:

```bash
python create_all_redirects.py
```

### ✅ TOP 30 URLs sind ready für Migration!

**Diese Redirects decken 83% deines lehmann.ws Traffics ab.**

---

## 📊 Traffic Breakdown:
- **TIER 1**: 4 URLs = 50% Traffic
- **TIER 2**: 7 URLs = 35% Traffic  
- **TIER 3**: 8 URLs = 21% Traffic
- **TIER 4**: 11 URLs = 12% Traffic

**Total**: 30 URLs = 83% Traffic Coverage
