# Enhanced Titanic Dataset with Advanced Features

This dataset extends the classic Titanic dataset with advanced engineered features that can help improve model performance. It's designed to help data scientists and machine learning practitioners achieve better results in the Titanic competition and learn effective feature engineering techniques.

## Dataset Description

This dataset includes all original Titanic features plus carefully engineered additional features that capture important patterns and relationships in the data. These engineered features are based on techniques used by Kaggle Grandmasters.

### Files
- `train_enhanced.csv`: Enhanced training dataset with survival information
- `test_enhanced.csv`: Enhanced test dataset
- `feature_descriptions.csv`: Detailed descriptions of all features
- `sample_submission.csv`: Example submission file

### Features

The enhanced features include:

1. **Title**: Extracted from passenger names (Mr, Mrs, Miss, etc.)
2. **FamilySize**: Total number of family members (SibSp + Parch + 1)
3. **IsAlone**: Binary indicator if passenger is traveling alone
4. **Deck**: Extracted from cabin information
5. **AgeGroup**: Categorized age ranges
6. **FareGroup**: Categorized fare ranges
7. **EmbarkedClass**: Interaction between embarkation port and passenger class
8. **GenderClass**: Interaction between gender and passenger class
9. **TitleClass**: Interaction between title and passenger class
10. **FamilyClass**: Interaction between family size and passenger class

## Usage

This dataset is particularly useful for:
- Learning effective feature engineering techniques
- Improving Titanic competition scores
- Educational purposes for data science students
- Benchmarking different machine learning algorithms

## Methodology

The features were engineered using a systematic approach:
1. Thorough exploratory data analysis to identify patterns
2. Careful handling of missing values
3. Creation of interaction features to capture relationships
4. Binning of continuous variables where appropriate
5. Extraction of information from text fields

## Acknowledgements

This dataset builds upon the original Titanic dataset provided by Kaggle. The feature engineering techniques are inspired by top-performing notebooks and Kaggle Grandmasters' approaches.

## License

This dataset is made available under the CC0: Public Domain license.
