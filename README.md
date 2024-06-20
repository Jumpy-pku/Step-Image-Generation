# Step Image Generation

[Demo](https://jumpy-pku.github.io/Step-Image-Generation/)

## theSpruceEats Dataset

- `recipe_step_image_data.json`: The JSON file containing the data for the recipe step image generation task. Each key in the JSON file is a recipe ID and the value is a dictionary. Each dictionary contains the following keys:
  - `title`: The title of the recipe.
  - `description`: The description of the recipe.
  - `ingredients`: A list of ingredients.
  - `steps`: A list of steps. Each step is a dictionary containing the following keys:
    - `text`: The text of the step.
    - `image_path`: The image file name of the step. The image file name is the key in the `images` folder.
  
- `images`: The folder containing images. Download `images.tar.gz` from [Google Drive](https://drive.google.com/file/d/1z2QPO-MIdAnfM1G7M2LpLY3q-GwgQwfT/view?usp=drive_link) and extract it into `images` folder.