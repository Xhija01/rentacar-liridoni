# 🚀 Publiko "Rent a Car Liridoni" FALAS në GitHub Pages

Kjo faqe është një **single-file** (HTML + CSS + JS në një skedar të vetëm), ideale
për ta publikuar **falas** në internet me **GitHub Pages**.

Në fund do të marrësh një link si ky:

```
https://emri-yt.github.io/rentacar-liridoni/
```

---

## ✅ Çfarë duhet

1. Një **llogari GitHub** falas — krijoje në [github.com](https://github.com/signup)
   nëse nuk e ke.
2. **VS Code** (që tashmë e ke) me skedarin `index.html` të hapur.
3. **Git** i instaluar në kompjuter (mund ta kontrollosh duke shkruar `git --version`
   në terminal).

---

## 📋 Pjesa 1 — Krijo llogarinë GitHub (vetëm herën e parë)

1. Shko te [github.com/signup](https://github.com/signup).
2. Plotëso email-in, fjalëkalimin dhe emrin e përdoruesit.
3. Verifiko email-in që të dërgon GitHub.
4. **Shëno emrin e përdoruesit** (username) — do ta duash më poshtë.
   Shembull: nëse emri yt është `arbri`, linku do të jetë
   `https://arbri.github.io/...`.

---

## 📋 Pjesa 2 — Krijo repositorin (dosjen) e ri në GitHub

1. Hyr në [github.com](https://github.com) me llogarinë tënde.
2. Kliko butonin **"+"** lart djathtas → **"New repository"**.
3. Në fushën **"Repository name"** shkruaj:
   ```
   rentacar-liridoni
   ```
4. Zgjidh **"Public"** (kërkohet që GitHub Pages falas të funksionojë).
5. **MOS** i vë shenjë "Add a README file" (e kemi tashmë).
6. Kliko **"Create repository"**.

⚠️ **Mos e mbyll këtë faqe** — do të të duhen hapat që shfaqen aty.

---

## 📋 Pjesa 3 — Ngarko projektin nga VS Code në GitHub

Meqë projekti është **tashmë i inicializuar me Git** dhe me **commit-in e parë**,
do ta bësh nga VS Code direkt:

1. Në VS Code hap dosjen `rentacar-liridoni`
   (File → Open Folder → zgjidh `rentacar-liridoni`).
2. Hap panë **Source Control** nga ikona majtas (ose `Ctrl+Shift+G`).
3. Në fushën e mesazhit shkruaj p.sh. `Publish website` dhe kliko **✓ Commit**
   (nëse ka ndryshime të pa-kryera).
4. Kliko **"Publish Branch"** ose **"Publish Repository"**.
   - Nëse VS Code të kërkon login, kliko **"Sign in to GitHub"** dhe
     autorizo në shfletues.
   - Zgjidh **"Publish to GitHub public repository"**.
   - Emri i repositorit: `rentacar-liridoni`.
5. Pasi të përfundojë ngarkimi, VS Code të tregon linkun e repositorit —
   kliko për ta hapur.

> 💡 **Alternativë me komandë (terminal):** Nëse preferon terminalin, shkruaj:
> ```
> git remote add origin https://github.com/EMRI-YT/rentacar-liridoni.git
> git branch -M main
> git push -u origin main
> ```
> (Zëvendëso `EMRI-YT` me emrin tënd të përdoruesit.)

---

## 📋 Pjesa 4 — Aktivizo GitHub Pages

**Mënyra më e thjeshtë (rekomandohet):**

1. Hap repositorin `rentacar-liridoni` në GitHub.
2. Kliko skedën **Settings** (⚙️).
3. Në menynë e majtë kliko **Pages** (te seksioni "Code and automation").
4. Te **"Build and deployment"** → **"Source"** zgjidh **"Deploy from a branch"**.
5. Te **"Branch"** zgjidh **`main`** dhe në menynë pranë saj **`/ (root)`**.
6. Kliko **"Save"**.

🎉 **U bë!** Pas 1–2 minutash, faqja jote do të jetë publike në:

```
https://EMRI-YT.github.io/rentacar-liridoni/
```

(zëvendëso `EMRI-YT` me emrin tënd të përdoruesit)

> ✅ **Automatik:** Pasi ta bësh këtë një herë, faqja publikohet **vetë** në çdo
> ndryshim që bën në `index.html` dhe e shtyn (Commit → Push) — pa asnjë hap shtesë.

---

## 🔁 Si të përditësosh faqen pas ndryshimeve

1. Ndrysho `index.html` në VS Code.
2. Hap **Source Control** → shkruaj mesazh → **Commit** → **Sync / Push**.
3. Pas disa sekondash (ose 1–2 minutash nëse përdor "Deploy from a branch"),
   ndryshimet shfaqen në linkun tënd.

---

## ✏️ Si t'i ndryshosh të dhënat (telefoni, adresa, email)

Të gjitha të dhënat janë në `index.html`. Hape me **Notepad** ose në VS Code
(`Ctrl+F`) dhe kërko:

| Çfarë | Kërko | Zëvendëso me |
|-------|-------|--------------|
| Numri WhatsApp | `355690000000` | numrin tënd real (pa +, pa hapësira) |
| Numri i shfaqur | `+355 69 000 0000` | numrin tënd të plotë |
| Adresa | `Rruga e Kavajës, Tiranë` | adresën tënde reale |
| Email | `info@rentacarliridoni.al` | email-in tënd real |

**Këshillë:** Butoni i WhatsApp dhe formulari i rezervimit dërgojnë mesazh automatik
në numrin që ke vendosur në `355690000000`. Ndryshoji **të gjitha** vendet ku shfaqet
ky numër (`Ctrl+H` → Replace All).

---

## ❓ Problemet e zakonshme

| Problem | Zgjidhja |
|---------|----------|
| Faqja jep **404** pas publikimit | Prit 1–2 minuta; sigurohu që te Settings → Pages zgjodhe **`main` / `(root)`**. |
| Linku nuk hapet | Kontrollo që repositori është **Public** (jo Private). |
| Dëshiron emër më të shkurtër | Krijo repo me emrin `EMRI-YT.github.io` dhe faqja do të jetë te `https://EMRI-YT.github.io/` — shiko [dokumentimin e GitHub Pages](https://docs.github.com/en/pages). |
| Dëshiron domain-in tënd (p.sh. `rentacarliridoni.al`) | Pasi aktivizohet Pages, te Settings → Pages → **Custom domain** shkruaj domain-in dhe ndiq udhëzimet e DNS. |

---

## 💡 Shënime

- Faqja është **responsive** — duket mirë në telefon, tablet dhe kompjuter.
- Ikona 📍 në hartë tregon Tiranën. Mund ta ndryshosh linkun e `iframe` të
  Google Maps në skedar.
- Fotoja e makinës në krye është një ilustrim SVG — nëse dëshiron foto reale,
  zëvendësoje me fotot tua.

---

© 2026 Rent a Car Liridoni

