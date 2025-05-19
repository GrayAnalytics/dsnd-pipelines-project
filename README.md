
# Fashion Forward Forecasting

In this project we're receiving customer reviews of clothing products, and trying to predict if they ultimately recommend said product.

## Getting Started

For this project, I used a virtual environment called 'virt_env', worked in VS Code, 
and used Python 3.12 as my python kernel.

### Dependencies
The original requirements file only had Scikit-learn, pandas, spacy, and notebook.  
It has now expanded greatly due to all the default packages included in a virtual environment. But required packages for this project are:
```
pandas
wordcloud
matplotlib
spacy
numpy
scikit-learn
pickle
```

### Installation

You'll need copy the github repo, install the required libraries, potentially create a virtual environment

```
1. Clone the github repository  
git clone https://github.com/GrayAnalytics/dsnd-pipelines-project
2. Navigate to dsnd-pipelines-project directory
cd dsnd-pipelines-project
3. Install required packages
python -m pip install -r requirements.txt
```

## Testing

Explain the steps needed to run any automated tests

### Break Down Tests

Explain what each test does and why

```
Examples here
```

## Project Instructions

Udacity provided instructions of what they expect for this project

## Built With

* Preprocessing - General data cleansing and exploration
* Text processing for use in pipeline - Text cleansing and normalization, TFIDF calculation
* Create features for pipeline - Create Dummy Variables/One-Hot Encoding of categorical data
* Create model pipeline that combines preprocessing, feature engineering, and model creation - create model pipeline that includes feature engineering, each data type pipeline, and model training
* Fine-tune model - Cross Validation
* Evaluate - Model accuracy calculation


## License

[License](LICENSE.txt)
