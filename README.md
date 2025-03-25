# Beauty Product Recommendation using RAG & Multimodal LLMs

## Overview
This project leverages **Retrieval-Augmented Generation (RAG)** and **Multimodal Large Language Models (LLMs)** to provide personalized beauty product recommendations based on the **Amazon Beauty Product Dataset**. By integrating **BLIP, CLIP, and Stable Diffusion**, we enhance recommendations using both textual and visual data.

## Technologies Used
- **RAG (Retrieval-Augmented Generation)**: Improves recommendation accuracy by combining retrieval-based insights with generative AI.
- **BLIP (Bootstrapped Language-Image Pre-training)**: Extracts textual insights from product images and descriptions.
- **CLIP (Contrastive Language-Image Pretraining)**: Matches visual and textual features for better product relevance.
- **Stable Diffusion**: Generates synthetic images to enhance product visualization.
- **Hugging Face Transformers & Diffusers**: For implementing LLMs and image models.
- **PyTorch**: Deep learning framework for model fine-tuning.

## Features
- **Multimodal recommendation**: Uses text, images, and reviews for accurate product suggestions.
- **Visual similarity matching**: Finds similar products using CLIP embeddings.
- **Personalized recommendations**: Tailors results based on user preferences and reviews.
- **Synthetic image generation**: Creates AI-generated product previews.

## Installation
```bash
# Clone the repository
git clone https://github.com/your-username/beauty-product-recommendation.git
cd beauty-product-recommendation

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
from recommender import BeautyRecommender

# Initialize the recommendation system
recommender = BeautyRecommender()

# Get recommendations based on product ID
recommendations = recommender.get_recommendations(product_id="B001234")
print(recommendations)
```

## Dataset
- **Amazon Beauty Product Dataset**: Available on Kaggle or AWS Open Data.

## Contributing
Feel free to open issues or submit pull requests to improve the project!

## License
MIT License. See `LICENSE` for details.
