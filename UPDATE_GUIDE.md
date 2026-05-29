# 🚀 AKTUALIZÁCIA APLIKÁCIE NA GITHUB

## Zmeny v tejto verzii:
- ✅ Responzívne škálovanie písma v archíve pomocou `clamp(10px, 2.8vw, 14px)`
- ✅ Dynamický Grid layout: automatická šírka pre dátum a flexibilné stĺpce pre čísla
- ✅ Uvoľnenie pixelov: zmenšenie bočných paddingov na mobiloch pre maximum miesta
- ✅ Zámok proti orezaniu dátumu (`white-space: nowrap`)
- ✅ Aktualizácia Service Workera na v44

## POSTUP - Skopíruj do Git Bash:

```bash
cd "c:\Users\doros\Desktop\Nový priečinok"
git remote set-url origin https://github.com/daneh471/Zdravie-test5.git
git add .
git commit -m "Update v44: Fully responsive archive scaling and auto-grid"
git push origin main --force
```

## ⏳ Čo s
1. GitHub aktualizuje stránku (1-2 minúty)
2. Service Worker detekuje zmenu (v33)
4. Stlačením **OK** sa app automaticky reloaduje
5. Nová verzia je načítaná! 🎉

## ✅ Hotovo!

Aplikácia na: https://daneh471.github.io/Zdravie-test5/
