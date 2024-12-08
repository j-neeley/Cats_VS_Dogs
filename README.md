# Cats VS Dogs
- Simple CNN using tensorflow trained on 16396 images of cats and dogs and validated with 7026 images.
## Running locally
- If you wish to run this code locally, you will have to install the dataset from [Kaggle](https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset).
- Then, run the "remove-images.py" script to delete corrupted images in the dataset (making sure the unzipped "PetImages" folder is in the same directory as the script).
- Next, open "BinaryClassifier.ipynb" in a Jupyter notebook.
- Make sure to pip install any packages included in the import statements that you do not already have installed.
- You should then be able to run the cells in the notebook. I ran the "model.fit" cell twice to achieve a total of 20 training epochs. This will take a while.
