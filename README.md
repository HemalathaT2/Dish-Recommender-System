# Dish Recommender System using Tkinter

This is a Dish Recommender System built using Tkinter, a Python GUI library. It collects user input such as available ingredients, difficulty level, cuisine, preparation time, and diet type (veg or non-veg) to recommend dishes based on the given criteria. The system displays the name of the dish, its image, required ingredients and quantities, and the recipe.

## Prerequisites

Make sure you have the following installed before running the application:
- Python (version 3 or above)
- Tkinter library
- PIL (Python Imaging Library) library
- Pandas library
- Requests library

You can install these dependencies using pip:

```shell
pip install tkinter
pip install pillow
pip install pandas
pip install requests
```

## Usage

To run the Dish Recommender System, follow these steps:

1. Clone the GitHub repository:
   ```shell
   git clone https://github.com/HemalathaT2/dish-recommender-system.git
   cd dish-recommender-system
   ```

2. Run the application:
   ```shell
   python dish_recommender.py
   ```

3. The GUI window will appear with input fields for ingredients, difficulty level, cuisine, preparation time, and diet type. Fill in the required information.

4. Click on the "Submit" button to get the recommended dishes based on your input.

5. The recommended dishes will be displayed with their names, images, required ingredients and quantities, and the recipe.

6. You can click on the "Clear" button to reset the input fields and get new recommendations.

## Dataset

The Dish Recommender System uses a dataset containing dishes' information such as names, images, ingredients, and recipes. The dataset is preprocessed and loaded into the system for recommendation purposes.

## Contribution

If you'd like to contribute to this project, you can follow these steps:

1. Fork the repository.

2. Create a new branch:
   ```shell
   git checkout -b feature/my-feature
   ```

3. Make your changes and commit them:
   ```shell
   git commit -m "Add my feature"
   ```

4. Push to the branch:
   ```shell
   git push origin feature/my-feature
   ```

5. Create a pull request on GitHub.

## Credits

The Dish Recommender System is developed by [Hemalatha T](https://github.com/HemalathaT2). The dataset used in the system is sourced from [Kaggle](https://www.kaggle.com/datasets/kishanpahadiya/indian-food-and-its-recipes-dataset-with-images).

## License

This project is licensed under the [MIT License](LICENSE).

