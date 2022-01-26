# Problem Statement 
In astronomy, stellar classification is the classification of stars based on their spectral characteristics. Electromagnetic radiation from the star is analyzed by splitting it with a prism or diffraction grating into a spectrum exhibiting the rainbow of colors interspersed with spectral lines. Each line indicates a particular chemical element or molecule, with the line strength indicating the abundance of that element. The strengths of the different spectral lines vary mainly due to the temperature of the photosphere, although in some cases there are true abundance differences. The spectral class of a star is a short code primarily summarizing the ionization state, giving an objective measure of the photosphere's temperature.

Most stars are currently classified under the Morgan–Keenan (MK) system using the letters O, B, A, F, G, K, and M, a sequence from the hottest (O type) to the coolest (M type). Each letter class is then subdivided using a numeric digit with 0 being hottest and 9 being coolest (e.g., A8, A9, F0, and F1 form a sequence from hotter to cooler). The sequence has been expanded with classes for other stars and star-like objects that do not fit in the classical system, such as class D for white dwarfs and classes S and C for carbon stars.

The aim of this task is to classify stars based on information given in the dataset.

## Dataset

The dataset used is the Stars dataset (https://www.kaggle.com/brsdincer/star-type-classification/download) from Kaggle. 

The 3 class labels are:

1. **Red Dwarf:** A star having substantially lower surface temperature, intrinsic luminosity, mass, and size than the sun
2. **Brown Dwarf:** A celestial object that is much smaller than a normal star and has insufficient mass to sustain nuclear fusion but that is hot enough to radiate energy especially at infrared wavelengths
3. **White Dwarf:** A star that is at the end of its life and is very hot, small, and dense
4. **Main Sequence:** The group of stars that on a graph of spectrum versus luminosity forms a band comprising 90 percent of stellar types and that includes stars representative of the stages a normal star passes through during the majority of its lifetime
5. **Super Giants:** A star of very great intrinsic luminosity and enormous size
6. **Hyper Giants:** A star that has an extremely high luminosity, mass, size and mass loss because of its extreme stellar winds


## Model(s) Used

The models used in this task are K-Nearest-Neighbours (KNN) and Decision Tree alogrithm.

**KNN :**
<br>
K Nearest Neighbor algorithm falls under the Supervised Learning category and is used for classification (most commonly) and regression. It is a versatile algorithm also used for imputing missing values and resampling datasets. As the name (K Nearest Neighbor) suggests it considers K Nearest Neighbors (Data points) to predict the class or continuous value for the new Datapoint.

The algorithm’s learning is:

1. Instance-based learning: Here we do not learn weights from training data to predict output (as in model-based algorithms) but use entire training instances to predict output for unseen data.

2. Lazy Learning: Model is not learned using training data prior and the learning process is postponed to a time when prediction is requested on the new instance.

3. Non -Parametric: In KNN, there is no predefined form of the mapping function.

**Decision Tree :**
<br>
Decision Tree algorithm belongs to the family of supervised learning algorithms. Unlike other supervised learning algorithms, the decision tree algorithm can be used for solving regression and classification problems too.

The goal of using a Decision Tree is to create a training model that can use to predict the class or value of the target variable by learning simple decision rules inferred from prior data(training data).

In Decision Trees, for predicting a class label for a record we start from the root of the tree. We compare the values of the root attribute with the record’s attribute. On the basis of comparison, we follow the branch corresponding to that value and jump to the next node.

## Future Work
N/A

