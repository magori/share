# share

Applications Android à essayer, distribuées sous forme d'APK.

## Applications

| Application | Version | Fichier | Taille | Android |
|---|---|---|---|---|
| BloX | 1.0.0-rc2 (version de test) | [blox/blox-1.0.0-rc2.apk](blox/blox-1.0.0-rc2.apk) | 3,8 Mo | 8.0 ou plus |

### BloX

Un jeu de blocs pour Android, avec plusieurs jeux réunis dans une seule application :

- **Classique** et **Moderne** : les blocs qui tombent, avec la réserve et la pièce fantôme en Moderne ;
- **Serrurier** : des serrures à remplir avec les bonnes pièces ;
- **Graine du jour** : la même partie pour tout le monde, chaque jour ;
- **Jardin musical** : chaque pièce posée joue sa note ;
- **Au tempo** et **Course** : des jeux qui se jouent en rythme avec la musique ;
- **Passerelle** (nouveau) : on construit un pont au-dessus d'un ravin, puis la mascotte le traverse en chantant.

La version 1.0.0-rc2 est une **version de test** : elle peut encore contenir des défauts.

## Installer un APK

1. Sur le téléphone, ouvrir le lien du fichier `.apk` ci-dessus, puis toucher **Download** (ou « Télécharger »).
2. Ouvrir le fichier téléchargé. Si Android le demande, autoriser l'installation d'applications depuis le navigateur
   ou le gestionnaire de fichiers (*Paramètres > Applications > Accès spécial > Installer des applications inconnues*).
3. Toucher **Installer**.

Une nouvelle version s'installe par-dessus l'ancienne : les records et les réglages sont gardés.

## Vérifier un fichier

Empreinte SHA-256 de chaque APK :

| Fichier | SHA-256 |
|---|---|
| `blox/blox-1.0.0-rc2.apk` | `7ad881a88fddcfc01aa71141541af71e60ed00683accfca7d2dcdf73320d27a6` |

Toutes les versions de BloX sont signées avec le même certificat, d'empreinte SHA-256
`3aafdae9b51875ec0aba04742dae2e27d915f62bc5b1d398f9f7dcdb2d1779b8`. Pour le vérifier :
`apksigner verify --print-certs blox-1.0.0-rc2.apk`.
