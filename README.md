Astra Vela Pro

La navigation astronomique et l'estime, réunies dans un seul logiciel.

Astra Vela Pro calcule vos éphémérides, réduit vos observations au sextant en droites de lieu, trace votre route et gère votre marée — entièrement hors ligne, sur votre ordinateur. Un outil d'aide au calcul moderne pour qui pratique encore le point astronomique.

⚠️ Outil d'aide au calcul et à l'entraînement à la navigation astronomique — non certifié pour la navigation réglementaire. Version 0.1.0 : logiciel jeune, susceptible de contenir des erreurs de jeunesse. Ne remplace pas les publications officielles ni les moyens de navigation réglementaires.

Téléchargement

👉 Télécharger la dernière version (gratuit, Windows & Linux)

Les deux éditions sont distribuées gratuitement, sans limite de durée ni de fonctions, sans création de compte.

Système	Format	Édition Standard	Édition Pro
Windows 10 / 11	.exe (installeur)	108 Mo	115 Mo
Linux (toutes distributions)	.AppImage (portable)	117 Mo	124 Mo
Linux (Debian / Ubuntu…)	.deb	109 Mo	113 Mo
Linux (Fedora / openSUSE…)	.rpm (non testé par l'auteur)	114 Mo	119 Mo
Standard vs Pro
Fonction	Standard	Pro
Éphémérides (Soleil / Lune / planètes / étoiles)	✓	✓
Point observé (réduction, Polaire, passage méridien, identification d'astre)	✓	✓
Point estimé	✓	✓
Route — loxodromie / orthodromie / composite	✓	✓
Droites de lieu + journal de bord chaîné SHA-256	✓	✓
Budget d'erreur	✓	✓
Fiche de réduction papier + almanach de secours	✓	✓
Contrôle du compas (azimut / amplitude)	✓	✓
Conversions, Définitions, éclipse solaire	✓	✓
Manuel imprimable, sauvegarde de session	✓	✓
Réception GPS (série / UDP / NMEA 2000 / SignalK) + simulateur	—	✓
Marée mondiale hors ligne (4 170 stations)	—	✓
Feuille de pointage (Mercator sécante) + carte du monde	—	✓
Homme à la mer (MOB) avec contrôle de fraîcheur	—	✓
Déviation du compas — table et courbe complète	—	✓
Recoupement WMM (variation magnétique)	—	✓
Thème visuel enrichi (icônes egui-phosphor)	—	✓
Conception
🦀 Écrit en Rust — application native, sans dépendance à un runtime externe ni à une connexion internet pour fonctionner.
💾 Sauvegarde automatique de la session (positions, observations, réglages) en cours d'usage.
🧪 Panneau d'auto-test intégré, accessible depuis l'onglet Aide, pour vérifier la cohérence des calculs.
🔒 Chaque droite de lieu est consignée dans un journal de bord chaîné par hachage SHA-256, garantissant qu'il n'a pas été modifié après coup.
Sources de données
Domaine	Source	Licence
Éphémérides planétaires	ANISE (Nyx Space) / JPL DE (NASA-JPL)	MPL-2.0 / domaine public
Étoiles & constellations	d3-celestial / Stellarium — 88 figures IAU	BSD
Marée mondiale (Pro)	TICON-4 (DGFI-TUM, GESLA-4) via la base Neaps — 4 170 stations	CC BY 4.0
Variation magnétique (Pro)	WMM — World Magnetic Model	domaine public
Fond de carte	Natural Earth	domaine public
À propos de ce dépôt

Ce dépôt sert de point de distribution officiel pour les binaires d'Astra Vela Pro (voir l'onglet Releases). Le code source du logiciel n'est pas publié ici.

Contact

Une question, un bug, une suggestion ? Écrivez à auriciel21@gmail.com.

Astra Vela Pro est édité par Auriciel, ancien commandant de la marine marchande.

Si le logiciel vous rend service, un don volontaire est possible via PayPal (lien disponible dans l'onglet Aide du logiciel).
