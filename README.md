# Fashion-Recommendation-System

A Deep Learning-Based Dress Recommendation System that delivers personalized fashion recommendations by suggesting visually similar garments and complementary outfit combinations through the integration of Computer Vision, Deep Learning, Color Theory, and Body Type Analysis.

---

## Features

- Style similarity recommendation using ResNet50 embeddings
- Color harmony analysis using K-Means clustering in HSV color space
- Body-type detection using MediaPipe Pose
- Similar item recommendation
- Complementary outfit recommendation
- Explainable recommendation scores
- Fashion compatibility analysis

---

##  Overview

This project introduces an intelligent fashion recommendation platform capable of generating both:

### Similar Item Recommendations
Find garments that closely match a user's preferred style.

### Complementary Outfit Recommendations
Build complete, visually appealing outfits that coordinate perfectly.

Unlike traditional recommendation systems that rely solely on basic similarity measures, this solution integrates visual style understanding, color harmony principles, and body-type compatibility to provide fashion-aware recommendations.

---

##  Key Features

###  Color Theory-Based Recommendations

- Detects dominant garment colors using advanced clustering techniques.
- Evaluates color harmony using fashion design principles.
- Supports monochromatic, analogous, complementary, and triadic color schemes.

###  Deep Learning Style Analysis

- Utilizes ResNet50 to extract rich visual style embeddings.
- Captures textures, silhouettes, patterns, and design elements.
- Enables highly accurate style similarity matching.

###  Body Type Awareness

- Uses pose estimation and body landmark analysis.
- Identifies body types including:
  - Hourglass
  - Pear
  - Rectangle
  - Inverted Triangle
- Recommends garments that enhance body proportions and overall appearance.

###  Dual Recommendation Engine

#### Style Consistency Mode
Recommends visually similar fashion items.

#### Outfit Builder Mode
Suggests complementary garments for complete outfit creation.

###  Explainable AI

Provides clear explanations for recommendations, including:

- Color compatibility reasoning
- Body-type suitability
- Outfit coordination logic
- Style matching insights

---

## Dataset

The project uses a curated subset of **5,047 fashion images** collected from a publicly available DeepFashion-based dataset.

The dataset contains multiple garment categories, including:

- Dresses
- Blouses & Shirts
- Pants
- Shorts
- Skirts
- Jackets & Coats
- Sweaters
- Leggings
- Rompers & Jumpsuits
- Tees & Tanks

### Dataset Preprocessing

- Image resizing (224 × 224)
- RGB conversion
- Data cleaning
- Category balancing
- Feature extraction preparation

---

## System Architecture

### 1. Data Collection & Preprocessing
- Image normalization and resizing

### 2. Feature Extraction
- ResNet50-based style embeddings
- Color analysis using K-Means clustering
- Body-type detection through pose estimation

### 3. Feature Enrichment
- Color harmony scoring
- Body compatibility modeling
- Outfit compatibility assessment

### 4. Recommendation Engine
- Similar item retrieval
- Complementary outfit generation
- Personalized ranking

### 5. Explanation Module
- Human-readable recommendation reasoning

---

## Main Process

### 1. Style Feature Extraction

A pre-trained ResNet50 model is used to generate 2048-dimensional feature embeddings that capture:

- Garment style
- Texture
- Visual appearance
- Design characteristics

### 2. Color Analysis

K-Means clustering is applied to identify dominant garment colors.

The system evaluates:

- Monochromatic combinations
- Analogous combinations
- Complementary combinations
- Triadic color relationships

### 3. Body-Type Detection

MediaPipe Pose is used to extract body landmarks and classify users into:

- Hourglass
- Pear
- Rectangle
- Inverted Triangle

### 4. Recommendation Engine

The recommendation score combines:

- Style Similarity
- Color Harmony
- Body-Type Compatibility
- Outfit Compatibility

Two recommendation modes are supported:

#### Similar Item Recommendation
Finds garments with similar visual style and appearance.

#### Complete Outfit Recommendation
Suggests garments that complement the uploaded clothing item and form a coordinated outfit.

---

## Project Workflow

1. Upload a garment image
2. Extract visual features
3. Detect dominant colors
4. Estimate body type
5. Calculate compatibility scores
6. Generate recommendations
7. Display explanations and results

---

## Technologies Used

### Deep Learning
- TensorFlow / Keras
- ResNet50

### Computer Vision
- OpenCV
- MediaPipe Pose

### Machine Learning
- Scikit-Learn
- K-Means Clustering

### Data Processing
- NumPy
- Pandas

### Visualization
- Matplotlib
- Jupyter Notebook

---

##  Performance Highlights

The system demonstrated strong recommendation quality across multiple evaluation metrics:

| Metric | Similar Items | Complementary Outfits |
|----------|----------|----------|
| Final Score | 0.800 | 0.909 |
| Style Similarity | 0.782 | 0.828 |
| Color Harmony | 0.925 | 0.925 |
| Body Fit | 1.000 | 1.000 |
| Outfit Compatibility | 0.900 | High Coordination |

These results demonstrate the effectiveness of combining Deep Learning, Color Theory, and Body-Type Analysis for personalized fashion recommendations.

### Key Achievements

- High-quality personalized fashion recommendations
- Excellent color harmony performance
- Strong body-type-aware styling
- Effective complete outfit generation
- Transparent and explainable recommendation process

---

##  Use Cases

- Personalized fashion shopping
- Outfit planning and styling assistance
- Fashion e-commerce platforms
- Virtual wardrobe management
- AI-powered personal styling applications

---

##  Future Enhancements

- Real-time mobile application integration
- Advanced 3D body analysis
- Seasonal and cultural fashion adaptation
- Pattern and texture intelligence
- User feedback learning loop
- Sustainability-aware fashion recommendations

---

##  Conclusion

This project demonstrates how Deep Learning and Computer Vision can transform fashion recommendation systems by moving beyond simple similarity matching toward intelligent, personalized, and explainable styling assistance. By integrating style recognition, color harmony, body-type analysis, and outfit compatibility, the system delivers recommendations that are both visually appealing and fashion-aware.

---

## Author

Developed as an academic project focused on applying Deep Learning and Computer Vision techniques to personalized fashion recommendation systems.

**Smart Fashion Meets Artificial Intelligence.**
