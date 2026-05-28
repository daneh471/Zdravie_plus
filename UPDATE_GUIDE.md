# 🚀 AKTUALIZÁCIA APLIKÁCIE NA GITHUB

## Zmeny v tejto verzii:
- ✅ Vypnutie zoomu pre video elementy (touch-action: none)
- ✅ Optimalizácia meta viewport (user-scalable=no)
- ✅ Fixná veľkosť videa pri pinch-zoome a double-tape
- ✅ Aktualizácia Service Workera na v33

## POSTUP - Skopíruj do Git Bash:

```bash
cd "c:\Users\doros\Desktop\Nový priečinok"
git remote set-url origin https://github.com/daneh471/Zdravie-test5.git
git add .
git commit -m "Update v33: Video zoom prevention and viewport lock"
git push origin main --force
```

## ⏳ Čo sa stane:

1. GitHub aktualizuje stránku (1-2 minúty)
2. Service Worker detekuje zmenu (v33)
4. Stlačením **OK** sa app automaticky reloaduje
5. Nová verzia je načítaná! 🎉

## ✅ Hotovo!

Aplikácia na: https://daneh471.github.io/Zdravie-test5/
