# NLTK_Text_Preprocessing_Analysis_and_Visualization

This repository contains Python scripts for text preprocessing, analysis, and visualization using NLTK and word clouds. The primary focus is on the text from "Harry Potter and the Sorcerer's Stone," but the techniques and methods are applicable to other text datasets as well.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [License](#license)
- [Notes](#notes)

## Overview

This project processes the text from Harry Potter and the Sorcerer's Stone for text analysis and visualization. It involves preprocessing the text through tokenization, punctuation removal, stopword elimination, and lemmatization. The analysis focuses on word frequency distribution, and visualizations in the form of word clouds are created to highlight the most frequent terms in the text, both from the original and processed data.

## Installation

To use the scripts in this repository, you'll need to have Python installed. Additionally, install the required Python packages using pip:

```bash
pip install nltk wordcloud matplotlib
```

After installing the required packages, you will also need to download additional NLTK resources.

```bash
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## Usage

**1. Preprocessing**: The preprocessing steps involve reading the text from a file, tokenizing it into sentences and words, removing punctuation, eliminating stop words, and applying lemmatization to normalize the words into their base forms. This ensures the data is clean and ready for further analysis.

**2. Analysis**: The analysis phase includes calculating the word frequency distribution of the processed text. It also includes checking how many distinct words remain after stop word removal and lemmatization. These steps help in understanding the key terms and their frequencies in the dataset.

**3. Visualization**: The visualization section generates two word clouds: one directly from the original text (after removing stopwords) and another from the preprocessed data. The first word cloud shows the most frequent terms as they appear in the original text, while the second provides a more refined visualization after preprocessing steps like punctuation removal and lemmatization.


## Data

The data for this project is extracted from a text file containing the contents of Harry Potter and the Sorcerer's Stone. The text is processed through various stages, starting with reading the file and then performing tokenization, stopword removal, punctuation filtering, and lemmatization. The dataset is used for text analysis tasks, focusing on word frequency distribution and generating word clouds based on processed text. The text data is then visualized to better understand the distribution of significant terms.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Notes

For any questions or issues, please feel free to open an issue or pull request in this repository.

Happy coding!
