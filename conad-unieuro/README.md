# CONAD + UNIEURO — Simulatore casse

Applicazione dimostrativa indipendente per la formazione: due casse CONAD e UNIEURO in una sola pagina.

## Apri il simulatore

https://theyaredeveloper.github.io/scoltool/conad-unieuro/

## Pannello admin backup

Nella schermata iniziale seleziona **ADMIN BACKUP · 7 COPIE**. Il progetto Supabase è già configurato nell'app: crea un account personale, conferma l'email se richiesta e accedi. Da lì puoi salvare un backup, visualizzare le ultime 7 versioni e ripristinarle.

Backup automatico dopo 24 ore quando il sito viene aperto o resta aperto. Su un dispositivo nuovo, ripristina prima il backup esistente per evitare di sovrascriverlo con i cataloghi iniziali. I dati locali rimangono nel browser fino a quando non sono salvati sul cloud.

Il database applica RLS per isolare i backup di ciascun account. Nel frontend è presente solo una chiave pubblica Supabase, mai una chiave privata.

## Hosting

Questa directory è pubblicata come sottopercorso del repository GitHub Pages esistente `scoltool`, senza sovrascriverne la pagina principale.

Questo progetto è una simulazione non ufficiale, non affiliata ai marchi citati.
