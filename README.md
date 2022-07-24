# Dependency-Analysis-KFoldCrossValidation
This repository is the python implementation of the article: https://ieeexplore.ieee.org/abstract/document/8012491

All the idea behind this implementation belongs to the writers of the mentioned article.

## Reproduction instruction
To reproduce the results

- First run `pip install -r requirments.txt`.
-  Download each datasets below, move and extract them in a folder named `Datasets`. 

    1. [Liver disorders](https://archive.ics.uci.edu/ml/datasets/liver+disorders) Path should be `Datasets/liver-disorders/bupa.data`

    2. [Letter recognition](https://archive.ics.uci.edu/ml/machine-learning-databases/letter-recognition/): Path should be `Datasets/letter recognition/letter-recognition.data`
    
    3. [MAGIC gamma telescope data](https://archive.ics.uci.edu/ml/datasets/magic+gamma+telescope): Path should be `Datasets/magic/magic04.data`

    4. [Page-Blocks dataset](https://archive.ics.uci.edu/ml/datasets/Page+Blocks+Classification): Path should be `Datasets/page-blocks/page-blocks.data`

    5. [Wine Quality dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality): Pathes should be 

        - `Datasets/wine-quality/winequality-red.csv`
        - `Datasets/wine-quality/winequality-white.csv`

    6. [Haberman's survival dataset](https://archive.ics.uci.edu/ml/datasets/haberman's+survival): Path should be 
    `Datasets/haberman/haberman.data`


- After that remove the folder `results` or move it to another location and make an empty folder with a same name. 

Finally run the all the cells in the `main.ipynb` notebook and wait for it to be finished.

