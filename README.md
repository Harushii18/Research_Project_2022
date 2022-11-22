# Convolutional Neural Network Model Building for Future Medicinal Plant Recognition
___
**Author**: Suraksha Motilal

**Student Number**: 2108903
_____

<ol>
<li>About the project:

Globally, it is estimated that 80% of the population makes use of traditional medicine to treat diseases. In the last century, correlations were found between traditional medicines and their pharmacological action, therefore pharmaceutical companies from abroad have since exploited medicinal plants from regions in Africa, including South Africa. Not only have pharmaceutical companies made use of these plants but, in the year 2000, 3 million South Africans used traditional medicines as primary health care \cite{Louw}, with the number growing over the years to 27 million in 2021.

Due to this growing demand for medicinal plants in South Africa, many areas have faced over-exploitation of these plants which threatens biodiversity . To solve this problem to an extent, the automatic classification of medicinal plants will be able to assist in the preservation of indigenous plant species by identifying the species and families that require conservation. This project aims to study the automatic recognition of indigenous South African medicinal plants to aid taxonomists in identifying these plants and assist the population that uses them for primary health care.

This project uses Convolutional Neural Networks to classify plant species, hoping to use these methods in the future on a future South African dataset.

<li>Datasets:

This project will not run without the datasets it is trained on. The code makes use of two image datasets: the [Healthy and Diseased Dataset](https://www.kaggle.com/datasets/amandam1/healthy-vs-diseased-leaf-image-dataset) and the [Flavia Dataset](https://flavia.sourceforge.net/). The image data for this project can be found in [this google drive folder](https://drive.google.com/drive/folders/1KxLdX5XZZHdAFNZJku5LiOItlNwhWO5f?usp=sharing)

<li>Models used:

A CNN was used and tested with various features as well as data augmentation techniques using [ImageDataGenerator](https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator).

**Please refer to the Research Report for further details.**


<li>Additional notes:

Although Transfer Learning was attempted, as seen in this repository, it was not mentioned in the Research Report as the methods resulted in too poor results. Other works did define that their model was trained for 1000 epochs, but due to early stopping and time constraints, that was not reached. 








