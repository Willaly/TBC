Trail Base Camp - maquette V1 (site statique, aucune compilation)

Contenu : index.html + dossier media/ (logo, photos, vidéos). Garder cette structure telle quelle.

Mise en ligne sur Vercel, le plus simple :
1. Aller sur vercel.com/drop (se connecter pour que le site reste en ligne).
2. Glisser ce .zip (ou le dossier décompressé) sur la page, nommer le projet, Deploy.
3. Envoyer l'URL obtenue à la personne qui relit.
Mise à jour : redéposer le dossier sur le projet dans le tableau de bord Vercel.

Alternative : dépôt GitHub importé dans Vercel (Framework "Other", aucune commande de build), ou "npx vercel" depuis ce dossier.

La page est en noindex (ligne <meta name="robots"> dans index.html) : à retirer au lancement public.
Les éléments surlignés en orange sont à valider. Le formulaire ne transmet rien (maquette).
