# GENAI_Project

Les scripts .py dans ce projet sont des scripts d'entraînement récupérés depuis Hugging Face, conçus pour appliquer la méthode DreamBooth, une technique permettant de fine-tuner des modèles de génération d'images à partir de données spécifiques. Chaque script a un rôle particulier selon la configuration et le modèle souhaité :

finetuning_XL_without_LORA.ipynb : Ce script permet de fine-tuner le modèle Stable Diffusion XL sans utiliser la méthode LoRA. 

finetuning_XL_with_LORA.ipynb : Ce script est conçu pour fine-tuner Stable Diffusion XL en utilisant la méthode LoRA. Cette technique est particulièrement utile lorsqu'on veut fine-tuner un modèle avec des ressources limitées, tout en maintenant une bonne performance sur des tâches spécifiques. Ici, nous appliquons LoRA pour optimiser l'entraînement tout en réduisant les coûts computationnels.

finetuning_v1_5.ipynb : Ce script sert à entraîner le modèle Stable Diffusion v1.5, en testant deux configurations d'étapes d'entraînement différentes, à savoir 400 et 800 étapes. Ce modèle est utilisé pour voir comment différentes durées d'entraînement affectent les performances et la qualité des images générées.

inference_models_comparaison.ipynb : Ce script permet de tester l'inférence des modèles avant qu'ils ne soient fine-tunés, afin d'avoir une base de comparaison claire des performances des différents modèles avant d'appliquer les ajustements. Cela permet de mieux comprendre l'impact des modifications effectuées lors du fine-tuning et d'évaluer l'amélioration des résultats.
