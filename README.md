# Shooter game with pose estimation
## To start the game
If already have the conda environment and requirements ready for the server, go to step 6; otherwise, start from step 1
1. Install [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html) with python version 3.9	
2. Create the environment from the `environment.yml` file:
    ```
    conda env create -f environment.yml
    ```
3. Verify that the new environment was installed correctly:
    ```
    conda env list
    ```
4. Activate the environment:
    ```
    conda activate shooterGame
    ```

5. Install python requirements
   ```
   pip install -r requirements.txt
   ```
6. Run the game : 
    ```
    python main.py
    ```