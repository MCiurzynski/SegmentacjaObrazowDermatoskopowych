# Analiza metod segmentacji obrazów dermatoskopowych

## Opis projektu
Projekt ma na celu analizę metod segmentacji obrazów dermatoskopowych. Są one porównywane przy pomocy IoU (Intersection over Union). Metody analizowane są przy pomocy zbioru zdjęć z konkursu ISIC 2018. Analizy dokonałem przy użyciu notatników Jupyter.

## Wymagania
W projekcie wykorzystałem środowisko [Conda](https://github.com/ageron/handson-ml3/blob/main/README.md). Jego konfiguracja znajduje się w pliku `environment.yml`. Można je stworzyć wpisując podane poniżej polecenia do terminala. W pliku uwzględniłem sterowniki Cuda które są wymagane do uruchomienia biblioteki TensorFlow na procesorze graficznym.
```bash
conda env create -f environment.yml
conda activate segmentation
```

## Zbiór zdjęć
Zdjęcia należy pobrać ze strony https://challenge.isic-archive.com/data/#2018, a następnie wypakować je w folderze `data` w korzeniu projektu. Należy pobrać zbiór treningowy, walidacyjny oraz testowy z zadania 1. Należy osobno pobrać obrazy oraz prawdziwe maski.

## Uruchomienie
Notatniki Jupyter można uruchomić od razu po stworzeniu środowiska i pobraniu zdjęć.

## Autor
Mateusz Ciurzyński
