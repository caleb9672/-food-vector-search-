

# 🍽️ Food Vector Search - Moteur de Recommandation

Moteur de recommandation basé sur la recherche vectorielle appliquée à un menu alimentaire.

Ce projet utilise la recherche vectorielle pour recommander des plats en fonction de la requête de l'utilisateur ou à partir des informations extraites d'un menu alimentaire en PDF.

## Fonctionnalités
- 📄 Extraction de texte depuis un fichier PDF
- 🧠 Génération d'embeddings avec Hugging Face
- 🔍 Recherche et recommandation via `chromadb`
- 🍽️ Suggestion de plats basée sur la similarité des descriptions

## 🛠️ Installation
Installez les dépendances nécessaires avant d'exécuter le notebook :

pip install PyPDF2 chromadb


## 🔑 API & Configuration
Le projet utilise les API suivantes :

Hugging Face (InferenceClient)
Google API (si nécessaire)

Ajoutez vos clés API dans le notebook :
- huggingface_api = "VOTRE_CLE"
- gemini_api = "VOTRE_CLE"


## 📊 Exemples de Résultats
Une fois le notebook exécuté, vous obtiendrez des recommandations basées sur la similarité des plats.

query = "I want a dish with egg, butter, and rice."

Recommandation :
- Top 1 Recommended Food Name: Salted Roasted Rice Crackers
- Top 2 Recommended Food Name: Garlic Bread
- Top 3 Recommended Food Name: Salted Roasted Mixed Seeds
- Top 4 Recommended Food Name: Pad Thai
- Top 5 Recommended Food Name: Vegetable Stir Fry

📜 Licence
Ce projet est sous licence MIT – vous pouvez l'utiliser, le modifier et le partager librement.
