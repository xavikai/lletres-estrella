# Lletres Estrella

**Juga-hi:** https://xavikai.github.io/lletres-estrella/

Joc per a tauleta separat per **temàtiques i assignatures del curs** (Castellà, Català, Matemàtiques i Anglès), amb la mascota Mochi, photocards, vestidor i minijocs interactius:

- **🩷 Castellà (Unidad 2 · Barcanova + reptes de nivell):**
  - **Diptongos e hiatos:** truc de vocals fortes i febles, classificació i separació en síl·labes (*aire, ciudad, caoba, día, rusgalía, vacío, reír, raíz, baúl, cereal…*).
  - **Cajas de hiperónimos:** relaciona hipònims amb el seu hiperònim (*telar → máquina, sol → estrella, cabaña → construcción, hilo → hebra, turquesa → color, brisa → viento…*), completa famílies i caça l'intrús.
  - **¡Fuera la palabra «cosa»! (Precisión léxica):** substitueix paraules comodí (*cosa, hacer, decir*) per vocabulari precís (*libreta, joya, setas, bandolera, construcción, fabricada, materiales…*).
  - **Taller de definiciones:** construeix definicions pas a pas (1r l'hiperònim + 2n les característiques pròpies) per a *brújula, jersey, explorador, cabaña, telar, microscopio…*
  - **Radar de oraciones:** diferencia **frase** (sense verb) i **oració** (amb verb) i classifica segons la intenció (**declarativa, interrogativa, exclamativa, imperativa, dubitativa**).
- **🟣 Català:**
  - **Ortografia i Dígrafs:** Caça-dígrafs (*rr, ss, ll, ny, qu, gu, tx, tz, ig, tg*), Eco (dictat de fitxes), Foto-memòria, Detectiu de famílies, Trucs (*-ava, -ia, m davant p/b*), Síl·labes boges, Paraules alienígenes.
  - **Llegir, escriure i Arcade:** Karaoke lector, Talla-frases, Posa els punts, Cursa de lletres, Conquesta lila.
- **🟢 Matemàtiques i Raonament:**
  - **Mates Estrella:** càlcul mental àgil, números amagats i problemes del curs.
  - **Laboratori de patrons:** sèries, matrius i balances d'equivalències.
- **🟡 Anglès:**
  - **Star English:** vocabulari i construcció de frases en anglès amb àudio.
- **Diccionari visual** amb emojis, **llibreta d'errors** amb repàs espaiat, **cartes de truc/xuletes** i **zona de pares**.

La lògica del joc és a `index.html`, sense dependències ni servidor propi. El progrés es desa al navegador (`localStorage`); a la Zona de pares es pot desar i recuperar una còpia.

## Instal·lació a la tauleta

- **Android:** obre [el joc](https://xavikai.github.io/lletres-estrella/) amb Chrome i tria **⋮ → Instal·la l'aplicació** (o **Afegeix a la pantalla d'inici**).
- **iPad:** obre'l amb Safari i tria **Compartir → Afegeix a la pantalla d'inici**.

L'aplicació guarda els fitxers del joc per poder obrir-lo sense connexió. Les fonts de Google poden canviar per les fonts del sistema si no hi ha internet. El progrés es desa en aquesta instal·lació del navegador; fes servir la còpia de seguretat de la Zona de pares per passar-lo a un altre dispositiu.

Els dictats fan servir la veu del sistema. Si el navegador no detecta una veu en **català**, el joc mostra instruccions per instal·lar-la i un enllaç al motor de veu de Google a Android. A l'iPad, la veu es tria a la configuració d'accessibilitat. Una web no pot descarregar ni activar una veu del sistema automàticament; un cop instal·lada, torna al joc i prem **comprova-ho**.
