# Lletres Estrella

**Juga-hi:** https://xavikai.github.io/lletres-estrella/

Joc per a tauleta per practicar l'ortografia en català (disortografia), amb una mascota, photocards i minijocs:

- **Ortografia:** Eco (dictat de fitxes), Foto-memòria, Detectiu de famílies, Trucs, Síl·labes boges, Paraules alienígenes (dictat de pseudoparaules)
- **Arcade:** Cursa de lletres, Conquesta lila
- **Llegir i escriure:** Karaoke lector, Talla-frases, Posa els punts
- **Raonament:** Laboratori de patrons (sèries, matrius i balances)
- **Diccionari visual** amb emojis, **llibreta d'errors** amb repàs espaiat i **zona de pares**

La lògica del joc és a `index.html`, sense dependències ni servidor propi. El progrés es desa al navegador (`localStorage`); a la Zona de pares es pot desar i recuperar una còpia.

## Instal·lació a la tauleta

- **Android:** obre [el joc](https://xavikai.github.io/lletres-estrella/) amb Chrome i tria **⋮ → Instal·la l'aplicació** (o **Afegeix a la pantalla d'inici**).
- **iPad:** obre'l amb Safari i tria **Compartir → Afegeix a la pantalla d'inici**.

L'aplicació guarda els fitxers del joc per poder obrir-lo sense connexió. Les fonts de Google poden canviar per les fonts del sistema si no hi ha internet. El progrés es desa en aquesta instal·lació del navegador; fes servir la còpia de seguretat de la Zona de pares per passar-lo a un altre dispositiu.

Els dictats fan servir la veu del sistema. Si el navegador no detecta una veu en **català**, el joc mostra instruccions per instal·lar-la i un enllaç al motor de veu de Google a Android. A l'iPad, la veu es tria a la configuració d'accessibilitat. Una web no pot descarregar ni activar una veu del sistema automàticament; un cop instal·lada, torna al joc i prem **comprova-ho**.
