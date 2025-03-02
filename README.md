

# 🍽️ Food Vector Search - Moteur de Recommandation avec ChromaDB

Ce projet utilise la recherche vectorielle pour recommander des plats en fonction de la requête de l'utilisateur ou à partir des informations extraites d'un menu alimentaire en PDF.

## Fonctionnalités
- 📄 Extraction de texte depuis un fichier PDF
- 🧠 Génération d'embeddings avec Hugging Face
- 🔍 Recherche et recommandation via `chromadb`
- 🍽️ Suggestion de plats basée sur la similarité des descriptions

## 🔑 API & Configuration
Le projet utilise les API suivantes :

Hugging Face (InferenceClient)
Google API (si nécessaire)

## 📊 Exemples de Résultats
Une fois le notebook exécuté, vous obtiendrez des recommandations basées sur la similarité des plats.

query = "I want a dish with egg, butter, and rice."

Recommandations :
- Top 1 Recommended Food Name: Salted Roasted Rice Crackers
- Top 2 Recommended Food Name: Garlic Bread
- Top 3 Recommended Food Name: Salted Roasted Mixed Seeds
- Top 4 Recommended Food Name: Pad Thai
- Top 5 Recommended Food Name: Vegetable Stir Fry

📜 Licence
Ce projet est sous licence MIT – vous pouvez l'utiliser, le modifier et le partager librement.
