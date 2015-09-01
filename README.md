In practice, data quality is bad (missing and incomplete). After cleansing and transforming dataset, we can conduct data mining.

# Exploratory analysis
* Number of instances: 300
* Number of attributes: 28
* Attribute information: attribute.csv

# Discretize and replace missing value
Using Weka filter Unsupervised/Attribute
* Normalize: Normalizes all numeric values in the given dataset (apart from the class attribute, if set). The resulting values are by default in [0,1] for the data used to compute the normalization intervals. But with the scale and translation parameters one can change that, e.g., with scale = 2.0 and translation = -1.0 you get values in the range [-1,+1].
* ReplaceMissingValue: Replaces all missing values for nominal and numeric attributes in a dataset with the modes and means from the training data.
* Discretize: An instance filter that discretizes a range of numeric attributes in the dataset into nominal attributes. Discretization is by simple binning. Skips the class attribute if set.
* NumericToNominal: A filter for turning numeric attributes into nominal ones. Unlike discretization, it just takes all numeric values and adds them to the list of nominal values of that attribute. Useful after CSV imports, to enforce certain attributes to become nominal, e.g., the class attribute, containing values from 1 to 5.
