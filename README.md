# 🔐 Admin · Journal de Nabie

Cet espace est un **panneau d’administration local** pour le blog _Journal de Nabie_.  
Il permet de gérer, depuis une seule interface :

- les articles du blog,
- les messages reçus,
- les abonnées newsletter,
- les souscriptions / programmes.

> ⚠️ Cet admin est pensé pour un usage **personnel** et **local**, pas comme un back-office professionnel en ligne.

---

## ✨ Fonctionnalités

- Tableau de bord avec récap (articles, messages, abonnées, programmes)
- Formulaire pour créer / modifier / supprimer des articles
- Liste des messages (avec détail + zone de réponse à copier-coller)
- Liste des abonnées newsletter
- Liste des programmes / souscriptions
- Interface moderne, rose & jaune, alignée avec le design du blog
- Données stockées dans le navigateur via `localStorage`

---

## 🔐 Accès admin (login)

L’accès à l’admin est protégé par un petit écran de connexion (login + mot de passe).

Le mot de passe **ne doit pas être committé sur GitHub** :  
il est chargé depuis un fichier de configuration local (**non versionné**), par exemple `config.local.js`.

---

## Screeshot
<img width="1672" height="837" alt="Screenshot 2025-11-25 121649" src="https://github.com/user-attachments/assets/b4b06bc2-f8cb-4052-b22d-d96eba998326" />

<img width="836" height="675" alt="Screenshot 2025-11-25 124050" src="https://github.com/user-attachments/assets/caff58a3-aef8-40d5-bf63-f80e7c4800f0" />



## 📁 Structure recommandée

```bash
journal-de-nabie-admin/
│
├── admin.html
├── admin.js          # (optionnel si tu sépares le JS)
├── config.local.js   # identifiants admin (NON commit sur Git)
├── README.md
└── .gitignore
