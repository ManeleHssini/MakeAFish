# MakeAFish

# 📄 Automatisation de l’insertion de photos dans les fiches sanitaires

Ce projet vise à automatiser l'insertion de photos d'identité dans les fiches sanitaires des enfants, afin de simplifier une tâche manuelle répétitive réalisée par les agents de la mairie d’Aulnay-sous-Bois.

Développée en Python, cette application propose deux modes : un traitement individuel et un traitement en batch (par lot), avec une interface utilisateur conviviale créée avec Streamlit.

---

## 🧠 Objectifs du projet

- ⏱ Gagner du temps sur le traitement administratif
- 🙅‍♀️ Réduire les erreurs humaines
- 🧾 Produire des fiches propres et homogènes
- 💸 Réaliser des économies (moins de personnel affecté à la tâche)
- 🧑‍💻 Proposer un outil simple, ergonomique, sans avoir besoin de coder

---

## 🛠 Fonctionnalités

- ✅ Insertion automatique d'une photo dans une fiche sanitaire PDF déjà remplie
- 🖼 Prise en charge des formats : `.jpg`, `.png`, `.pdf` (pour les photos)
- 📐 Recadrage automatique et redimensionnement de l’image
- 📌 Positionnement précis de la photo sur la fiche (en haut à droite)
- 🗂 Traitement individuel ou en **batch** (avec nomenclature identique)
- 🌐 Interface utilisateur accessible via navigateur (Streamlit)

---

## 💻 Interface Streamlit

L’interface a été conçue avec [Streamlit](https://streamlit.io), permettant à tout agent de charger des fichiers, de lancer l’insertion et de récupérer directement un PDF finalisé.

📸 *Aperçu de l'application :*

![aperçu](assets/interface.png) <!-- Remplace par une vraie capture si tu veux -->

---

## 📁 Arborescence du projet

📂 insertion-photos-fiches-sanitaires
├── main.py # Script principal
├── utils.py # Fonctions utiles (traitement images / PDF)
├── requirements.txt # Dépendances Python
├── README.md # Ce fichier
└── assets/

## 🧰 Procédure d’installation détaillée

Une version illustrée de la procédure est disponible ici :

📎 [Voir la diapo d'installation](docs/procedure_installation.pdf)
