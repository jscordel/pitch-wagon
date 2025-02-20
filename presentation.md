## Détecter la désinformation climatique 📝   
## *et rester cohérent avec un modèle frugal* 
  
---  
Le Wagon — Data Science #1820

## DEPART 🚀  
**🎯 Objectif**  
Développer le modèle le plus *performant* (% accuracy) et *frugal* (Wh) pour la détection de désinformation lié au climat dans des textes.

**📊 Données**  
[6k citations (EN) catégorisées suivant 8 étiquettes de désinformation](https://huggingface.co/datasets/QuotaClimat/frugalaichallenge-text-train)  
Train : 4,87k lignes  
Test : 1,22k lignes  

## PISTES 🗺️  
- Fine tuning de modèles : pré-LLM (ie: BERT), petit Language Model à fine-tuner (ie: Qwen)
- Finetuning des embeddings
- Finetuning de classifier : Random forests, Log regression, MLP, ..
- *Et bien d’autres*  🥰

## ARRIVEE 🏁  

**Désinformation**  
Donne moi un texte et je te dirai s'il est falacieux 🔮  
![Alt Text](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExaDRzYzNwY3NwMHJnMjhwejA3c2VlcG5pdGJjd3Zua2NpdmRza2VrZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/yxx6hlbDZ4Q6MX3rS4/giphy.gif)

## ARRIVEE 🏁  

**⚡️ Energy?**  
... et combien d'énergie j'ai consommé pour cette inférence.  
![Alt Text](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExaHYwbWoxcmswcTIxYW5qdjVqeXlxcmhmcHV3cWM1eDR5cmhvYnBmNiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/BJtFvZfq32ty99kvXw/giphy.gif)
