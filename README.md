# Training Mochi

**Juga-hi:** https://xavikai.github.io/lletres-estrella/

Joc per a tauleta separat per **temàtiques i assignatures del curs** (Castellà, Català, Matemàtiques i Anglès), amb la mascota Mochi, photocards, vestidor i minijocs interactius:

- **🩷 Castellà (5.º de Primaria):**
  - **Diptongos e hiatos:** truc de vocals fortes i febles, classificació i separació en síl·labes (més de 65 paraules, incloent-hi *h* intercalada: *aire, ciudad, caoba, día, rusgalía, vacío, búho, almohada, prohibir, vehículo…*).
  - **Agudas, llanas y esdrújulas:** identifica la síl·laba tònica, classifica la paraula i decideix si porta tilde segons la normativa.
  - **Duelo de letras (Ortografía 5.º):** reptes de *b/v* (*-aba, -bir, hervir/servir/vivir, -ivo*), *g/j* (*-ger/-gir, tejer/crujir, -aje*), *h* (*hie-, hue-, ha/a*), *ll/y* i *c/z*.
  - **Cajas de hiperónimos:** relaciona hipònims amb el seu hiperònim (28 famílies lèxiques), completa grups i caça l'intrús.
  - **¡Fuera la palabra «cosa»! (Precisión léxica):** substitueix paraules comodí (*cosa, hacer, decir, poner, abrir*) per vocabulari precís (*libreta, joya, setas, bandolera, esculpe, hornea, inaugurar, confecciona…*).
  - **Taller de definiciones:** construeix definicions pas a pas (1r l'hiperònim + 2n les característiques pròpies) per a 18 conceptes de 5è.
  - **Radar de oraciones:** diferencia **frase** (sense verb) i **oració** (amb verb) i classifica segons la intenció (**declarativa, interrogativa, exclamativa, imperativa, dubitativa**).
  - **Categorías, prefijos y sufijos:** substantius, adjectius, verbs, determinants, pronoms, adverbis, preposicions, prefixos/sufixos i homòfons (*tubo/tuvo, valla/vaya, hecho/echo*).
- **🟣 Català (5è de Primària):**
  - **Accents i dièresi:** agudes, planes i esdrúixoles, accent obert i tancat, diacrítics i ús de la dièresi (*veïna, raïm, pingüí, llengües*).
  - **So de la S i de la G/J:** practica *s/ss/c/ç/z* (sorda i sonora) i *g/j/tg/tj* (*platja, viatge, metge, boja, jersei*).
  - **Gramàtica i apòstrof:** regles i excepcions de l'apòstrof (*l'illa, la universitat, la una, el iogurt*), contraccions (*al, del, pel*), *per què / perquè*, pronoms febles i categories gramaticals.
  - **Ortografia i Dígrafs:** Caça-dígrafs (completar i separar en síl·labes), Eco (90 paraules de dictat de fitxes), Foto-memòria, Detectiu de famílies (68 paraules), Trucs (*-ava, -ia, m davant p/b, g/j, c/ç*), Síl·labes boges (56 paraules), Paraules alienígenes (70 pseudoparaules).
  - **Llegir, escriure i Arcade:** Karaoke lector (12 cançons i textos), Talla-frases (30 frases), Posa els punts (20 textos), Cursa de lletres, Conquesta lila.
- **🟢 Matemàtiques i Raonament (5è de Primària):**
  - **Mates Estrella:** càlcul mental àgil (jerarquia amb parèntesis, divisions, ×10/×100), números amagats i problemes de 5è.
  - **Fraccions, decimals i %:** fracció d'una quantitat, fraccions equivalents, comparació i operacions amb decimals i percentatges.
  - **Mesura, temps i geometria:** conversions d'unitats (*km, m, cm, kg, g, L, mL, hores*), angles, polígons, perímetre i àrea.
  - **Laboratori de patrons:** sèries, matrius i balances d'equivalències.
- **🟡 Anglès (5th Grade):**
  - **Star English:** vocabulari, definicions i construcció de frases en anglès amb àudio.
  - **Nature Explorer:** vocabulari de la naturalesa (*landscapes & landforms, plants & trees, weather & sky phenomena, forest & ocean wildlife, habitats* i *eco-actions*) amb guia visual i àudio.
  - **Grammar & Reading 5th:** *Present Simple vs Continuous, Past Simple, Comparatives & Superlatives, Going to, Must/Mustn't* i comprensió lectora amb àudio.
- **Diccionari visual** amb emojis, **llibreta d'errors** amb repàs espaiat, **cartes de truc/xuletes** i **zona de pares**.

La lògica del joc és a `index.html`, sense dependències ni servidor propi. El progrés es desa al navegador (`localStorage`); a la Zona de pares es pot desar i recuperar una còpia.

## Instal·lació a la tauleta

- **Android:** obre [el joc](https://xavikai.github.io/lletres-estrella/) amb Chrome i tria **⋮ → Instal·la l'aplicació** (o **Afegeix a la pantalla d'inici**).
- **iPad:** obre'l amb Safari i tria **Compartir → Afegeix a la pantalla d'inici**.

L'aplicació guarda els fitxers del joc per poder obrir-lo sense connexió. Les fonts de Google poden canviar per les fonts del sistema si no hi ha internet. El progrés es desa en aquesta instal·lació del navegador; fes servir la còpia de seguretat de la Zona de pares per passar-lo a un altre dispositiu.

Els dictats fan servir la veu del sistema. Si el navegador no detecta una veu en **català**, el joc mostra instruccions per instal·lar-la i un enllaç al motor de veu de Google a Android. A l'iPad, la veu es tria a la configuració d'accessibilitat. Una web no pot descarregar ni activar una veu del sistema automàticament; un cop instal·lada, torna al joc i prem **comprova-ho**.
