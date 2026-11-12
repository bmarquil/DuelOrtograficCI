# 🚀 Duel Ortogràfic 1 vs 1 (Català)

Aplicació web educativa interactiva dissenyada per practicar per parelles (**1 vs 1 simultani**) l'ortografia de la llengua catalana (**R / RR**, **B / V** i **C / QU**) en pissarres digitals interactives (PDI), tauletes i ordinadors.

---

## ✨ Característiques principals

* **Mode 1 vs 1 simultani:** Pantalla dividida perquè dos alumnes competeixin alhora sense interferir-se.
* **Disseny Touch-First:** Botons de grans dimensions (mínim `64x64px` / `115px`), tipografia d'alta llegibilitat a distància i bloqueig de selecció de text i zoom accidental.
* **Configuració per al docent:** Selecció prèvia de la norma ortogràfica (`R / RR`, `B / V`, `C / QU` o `Tot barrejat`) i del nombre d'encerts necessaris per completar la missió (`5`, `10` o `15` paraules).
* **Gamificació amb coet i cronòmetre:**
  * Cada jugador té un **coet (`🚀`)** que s'enlaira cap al planeta (`🪐`) amb cada encert i descendeix si es comet un error.
  * **Cronòmetre individual** d'alta precisió (`MM:SS.d`) que determina el guanyador al podi final.
* **Efectes de so integrats:** Àudio generat dinàmicament amb la *Web Audio API* (sense dependències ni fitxers externs), amb botó de silenci.
* **Mode Pantalla Completa:** Botó integrat per aprofitar el `100%` de la pissarra digital sense barres de desplaçament (`no-scroll`).

---

## 🌐 Com utilitzar l'aplicació amb GitHub Pages

Aquesta aplicació està desenvolupada en un **únic fitxer HTML autocontingut** (sense frameworks ni dependències externes), la qual cosa permet executar-la directament des de **GitHub Pages** sense cap instal·lació:

1. Puja els fitxers al teu repositori de GitHub (assegura't que el fitxer principal es digui `index.html` o accedeix-hi pel seu nom de fitxer).
2. Ves a **Settings** (Configuració) del repositori > **Pages** (al menú lateral esquerre).
3. A l'apartat **Build and deployment > Branch**, selecciona la branca `main` (carpeta `/root`) i fes clic a **Save**.
4. Al cap d'uns segons, GitHub publicarà l'enllaç públic (ex. `https://bmarquil.github.io/nom-del-repositori/`) llest per obrir-lo des de qualsevol navegador o pissarra digital de l'aula.

> 💡 **Ús fora de línia (Offline):** També pots descarregar el fitxer `.html` i obrir-lo directament fent doble clic en qualsevol navegador, fins i tot sense connexió a Internet.

---

## 🛠️ Tecnologies utilitzades

* **HTML5** semàntic i responsive (`100vw` / `100vh`).
* **CSS3** (Flexbox, Grid, animacions `@keyframes` i variables personalitzades).
* **JavaScript (ES6+)** pur amb *Web Audio API* i *Fullscreen API*.

---

## 👤 Autoria

App creada per **[@bmarquil](https://github.com/bmarquil)** a GitHub.