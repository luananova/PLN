# Discovering User Semantics and Concerns through NLP

## Project Overview
As a Master’s student specializing in Data Storytelling, this project leverages Natural Language Processing (NLP) techniques to analyze user feedback on Avenue's Reclame Aqui page. 
The objective is to identify key topics and user semantics within the negative feedback, thus providing Avenue's UX team with actionable insights and establishing a data-driven controlled vocabulary.

### What is NLP?
Natural Language Processing (NLP) involves programming computers to process and analyze large amounts of natural language data. 
It aims to understand and derive meaningful information from human language in a smart and useful way.

## Project Workflow

### 1. Data Collection
- **Tool Used**: Octoparse
- **Description**: User comments were gathered from Avenue's page on Reclame Aqui using Octoparse to scrape data directly from the web.

### 2. Data Preparation
- **Tool Used**: Python
- **Description**: The scraped data was cleaned and structured using Python, making it ready for analysis.

### 3. Grammatical Decomposition
- **Tool Used**: SpaCy
- **Description**: Analyzed parts of speech within the feedback to gain deeper linguistic insights.

### 4. Topic Analysis
- **Tool Used**: LDA Model
- **Description**: Applied Latent Dirichlet Allocation (LDA) to uncover prevalent themes within the feedback.

### 5. Visualization
- **Methods**: Heatmaps and Word Clouds
- **Purpose**: Translated the analysis findings into visual formats to highlight key linguistic trends and topics.

## Insights & Outcomes

### Parts of Speech Analysis
- Revealed a blend of informal language and formal expressions within the feedback, highlighting the varying communication preferences across different platforms.

### Key Topic Associations
- Identified critical topics such as Fees, Cards, Inactivity, Charges, Cancellation, Account, and Closure, directing targeted improvements to enhance user engagement.

## Conclusions
- The project advanced academic knowledge in NLP and provided practical insights beneficial for content design.
- Established a controlled vocabulary to standardize communication and ensure clarity.
- Set the groundwork for future projects to automate internal tools and expand analysis, enhancing NLP applications in real-world scenarios.

## How to Use This Repository

### Data Files
- The necessary data files for running the analysis are located in the `DATA` folder of this GitHub repository. Ensure you have these files downloaded and accessible before starting the notebook.

### Access the Notebook
- **Access the Notebook**: [Click here to access the project notebook](https://colab.research.google.com/drive/1_SqkuyQWb_Utz1rHsqS2gtpan3JkeIX8?usp=sharing)

### Run the Analysis
- Open the notebook link provided.
- Once the notebook is open in your browser, you can run the cells sequentially to see the analysis process and results.
- To run a cell, click on it and then press the play button or use the shortcut `Shift + Enter`.

### Make Your Own Modifications
- If you wish to modify or experiment with the analysis, you can save a copy of the notebook to your Google Drive.
- Click `File` > `Save a copy in Drive...` to create your own version of the notebook.

## Contributions
Contributions are welcome! Please feel free to fork the project, make changes, and submit pull requests if you have suggestions or improvements.
