# Image Classification Model: Is It a Bird?

This project demonstrates how to create an image classification model using custom data. The goal is to classify images into two categories: birds and forests. The project utilizes Fastai and DuckDuckGo Search for image scraping and model training.

## Project Overview

This project guides you through the following steps:
1. **Installing Dependencies**: Ensure all necessary libraries are installed, including `duckduckgo_search` and `fastai`.
2. **Image Search and Download**: Use DuckDuckGo to search and download images for both bird and forest categories.
3. **Data Preparation**: Organize and resize the downloaded images to prepare them for model training.
4. **Model Training**: Create a data loader, define a convolutional neural network (CNN) using ResNet18 architecture, and train the model on the dataset.
5. **Prediction**: Use the trained model to make predictions on new images.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook or Jupyter Lab
- Kaggle account (if running on Kaggle)
- Git (for version control)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   
## Usage

### Step 1: Search and Download Images

The `search_images` function uses DuckDuckGo to find and download images. We search for three variations for each category: regular, sunny, and shaded photos.

### Step 2: Data Preparation

Create a DataBlock and a DataLoader to handle the images.

### Step 3: Model Training

Define and train a CNN using the ResNet18 architecture.

### Step 4: Making Predictions

Use the trained model to predict whether a new image is a bird or not.


## Contributing
Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.
