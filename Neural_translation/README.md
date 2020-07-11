# Neural-Translation

## Why to do this project?
* You will create a neural network that translates from English to German.
* You will use concepts including building more flexible model architectures, freezing layers, data processing pipeline and sequence modelling.
* To brush up skills in model construction, training, evaluation and prediction using lower level API of Tensorflow 2.2.0
* Preprocessing and prediction part also brush up your skills in using re and numpy modules in python.

## Language Dataset
* We will use a language dataset from http://www.manythings.org/anki/ to build a neural translation model.
* This dataset consists of over 200,000 pairs of sentences in English and German. 
* In order to make the training quicker, we will restrict to our dataset to 20,000 pairs. Feel free to change this if you wish.

### How the data looks

English + TAB + The Other Language + TAB + Attribution
* This work isn't easy.	この仕事は簡単じゃない。	CC-BY 2.0 (France) Attribution: tatoeba.org #3737550 (CK) & #7977622 (Ninja)
* Those are sunflowers.	それはひまわりです。	CC-BY 2.0 (France) Attribution: tatoeba.org #441940 (CK) & #205407 (arnab)
* Tom bought a new car.	トムは新車を買った。	CC-BY 2.0 (France) Attribution: tatoeba.org #1026984 (CK) & #2733633 (tommy_san)
* This watch is broken.	この時計は壊れている。	CC-BY 2.0 (France) Attribution: tatoeba.org #58929 (CK) & #221604 (bunbuku)

### Import the data
* The dataset is available for download as a zip file at the following [Link](https://drive.google.com/open?id=1KczOciG7sYY7SB9UlBeRP1T9659b121Q).
* You should store the unzipped folder in Drive for use in this Colab notebook.
* For more information 

