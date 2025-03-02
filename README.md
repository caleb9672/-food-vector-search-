

# 🍽️ Food Vector Search - Moteur de Recommandation

Moteur de recommandation basé sur la recherche vectorielle appliquée à un menu alimentaire.

Ce projet utilise la recherche vectorielle pour recommander des plats en fonction du texte extrait d'un menu alimentaire en PDF.

## 🚀 Fonctionnalités
- 📄 Extraction de texte depuis un fichier PDF
- 🧠 Génération d'embeddings avec Hugging Face
- 🔍 Recherche et recommandation via `chromadb`
- 🍽️ Suggestion de plats basée sur la similarité des descriptions

## 🛠️ Installation
Installez les dépendances nécessaires avant d'exécuter le notebook :
```bash
pip install PyPDF2 chromadb

🔑 API & Configuration
Le projet utilise les API suivantes :

Hugging Face (InferenceClient)
Google API (si nécessaire)
Ajoutez vos clés API dans le notebook :
huggingface_api = "VOTRE_CLE"
gemini_api = "VOTRE_CLE"
