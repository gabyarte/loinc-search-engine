# LOINC Search Engine (UPM's Master in Data Science)

## Collaborators
* Pablo Bande Sánchez - Girón ([@pbande](https://github.com/pbande))
* Erick Abdiel Cedeño Guerra ([@erick4556](https://github.com/erick4556))
* Gabriela Argüelles Terrón ([@gabyarte](https://github.com/gabyarte))

## Run the project

To run the project is important to configure a virtual environment. For that, install Anaconda and type in a command line the following statement:

```bash
> conda env create -f environment.yml
```

After this command a new virtual environment called `search-engine` should be created. To active it, type the following command in the command line:

```bash
> conda activate search-engine
```

The project is implemented in two notebooks. These contain all the logic of our toy search engine:

* `1_preprocess`: This notebook contains the logic of the dataset preprocessing and has as output the preprocessed dataset. It is saved in the `data/` folder.
* `2_process`: This notebook contains the implemented Logistic Regression model and the validation.
