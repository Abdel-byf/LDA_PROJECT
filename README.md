# Latent Dirichlet Allocation (LDA) Project
## Project Overview
This project was undertaken as part of a research internship at Institut Élie Cartan in Nancy, France, from March to June 2021. The main objective of the project was to explore and apply the Latent Dirichlet Allocation (LDA) model for topic modeling on textual data. The work involved a comprehensive literature review, data preparation, and the application of LDA using the scikit-learn library in Python.

## Project Structure
The project is structured into several key parts:

### 1- Literature Review
Conducted an in-depth review and analysis of a scientific paper on LDA, particularly focusing on the work by David Blei, Andrew Ng, and Michael Jordan.

### 2- Data Preparation
Cleaned and prepared textual data from two sources:
- The 20 Newsgroups dataset
- Novels by Albert Camus (The Rebel, The Misunderstanding, The Myth Of Sisyphus)
<img src="https://github.com/Abdel-byf/LDA_PROJECT/assets/112027405/fb66f60e-027f-4965-aacd-b49cbc40a8d8" alt="philosopher" width="600" height="400">

### 3- Application of LDA
Applied LDA using scikit-learn to extract significant topics from the datasets.
Evaluated the results to ensure coherence with the known themes of the documents.


## Results
### 20 Newsgroups Dataset
The LDA model successfully extracted significant topics from the 20 Newsgroups dataset. The topics identified were consistent with the newsgroup categories, indicating that the model was effective in distinguishing between different themes present in the dataset.

- **Topic 9** represented by words like: city, town hall, work, municipality, municipal, union, public, land… can refer to the subject of the CITY.
- **Topic 5 and Topic 2** represented by words like: Price, customer, consumption, company, order, factory… refer to the subject of the COMPANY (ENTREPRISE in French).

The model returns a list of probabilities of belonging to a topic as follows:


### Albert Camus' Novels
The LDA model also successfully extracted significant topics from the novels of Albert Camus. The identified topics aligned well with the known themes and subject matter of his works, showcasing the model's capability to capture intricate thematic elements in literary texts.

- **Topic 1** represented by words like: absurd, rebellion, human condition, existentialism, freedom, meaning… reflects the existential and philosophical themes central to Camus' works.
- **Topic 7** represented by words like: myth, Sisyphus, struggle, life, happiness, absurdity… directly correlates with the themes explored in "The Myth of Sisyphus".

The consistency score we obtained for this model was acceptable. The figure below indicates that we have succeeded in identifying topics with an acceptable distance, i.e., there is no overlap between the topics.






The LDA model successfully extracted significant topics from both datasets. The topics identified from the 20 Newsgroups dataset were consistent with the newsgroup categories, and the topics from Albert Camus' novels aligned well with the known themes and subject matter of his works.

## Conclusion
This project demonstrated the application of LDA for topic modeling on diverse textual data. The results validated the effectiveness of LDA in uncovering hidden thematic structures in text, providing a valuable tool for organizing and summarizing large collections of documents.

## References
Blei, D. M., Ng, A. Y., & Jordan, M. I. (2003). Latent Dirichlet Allocation. Journal of Machine Learning Research, 3, 993-1022.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
