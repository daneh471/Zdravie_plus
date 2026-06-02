# 🚀 AKTUALIZÁCIA APLIKÁCIE NA GITHUB

## Zmeny v tejto verzii:
- ✅ Rozdelenie archívu: Aktuálny mesiac + tlačidlo pre staršie mesiace
- ✅ Dynamické rozbaľovanie histórie
- ✅ Úprava zobrazenia verzie na v3.3
- ✅ Aktualizácia Service Workera na v3.3

## POSTUP - Skopíruj do Git Bash:

```bash
cd "c:\Users\doros\Desktop\Programovanie\zdravieplus"
git remote set-url origin https://github.com/daneh471/Zdravie_plus.git
git add .
git commit -m "Update v3.3: Archive with current month and expandable history"
git push origin main --force
```

## ⏳ Čo s
1. GitHub aktualizuje stránku (1-2 minúty)
2. Service Worker detekuje zmenu (v3.0)
4. Stlačením **OK** sa app automaticky reloaduje
5. Nová verzia je načítaná! 🎉

## ✅ Hotovo!

GitHub Pages: https://daneh471.github.io/Zdravie_plus/
Vercel: zdravie-plus-ma1j.vercel.app