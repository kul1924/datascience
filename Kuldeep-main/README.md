
## Task 1: Exploratory Data Analysis (EDA)

### Objective
- **Load and clean the dataset** to remove any inconsistencies and prepare it for analysis.
- **Statistical summaries and visualizations** were performed to understand the key features in the dataset.
- **Business Insights** were extracted from the dataset to guide further analysis and decision-making.

### Key Steps:
1. Load the dataset and handle missing values.
2. Generate statistical summaries to understand central tendencies and distributions.
3. Create visualizations (e.g., histograms, box plots, heatmaps) to detect trends and outliers.
4. Extract at least **5 key business insights** from the dataset.

### Files:
- `eda_notebook.ipynb`: Jupyter notebook with the EDA steps.
- `insights_report.pdf`: A report summarizing key insights from the data analysis.

## Task 2: Lookalike Model

### Objective
- The goal is to identify customers with similar purchasing behavior using **Cosine Similarity** or **K-Nearest Neighbors (KNN)**.

### Key Steps:
1. **Feature Engineering**: Aggregate customer transactions, encode categorical features, and normalize numerical data.
2. **Similarity Computation**: Use **Cosine Similarity** or **KNN** to compute similarities between customers.
3. **Recommendation Generation**: For the first 20 customers (C0001 to C0020), recommend the top 3 most similar customers.

### Files:
- `lookalike_model_notebook.ipynb`: Jupyter notebook that contains the implementation of the Lookalike Model.
- `FirstName_LastName_Lookalike.csv`: CSV file containing the recommendations for each customer.

## Task 3: Customer Segmentation (Clustering)

### Objective
- Segment customers into different groups based on their profiles and transactions using **Clustering** techniques.

### Key Steps:
1. **Feature Extraction**: Extract features related to customer demographics and transactions.
2. **Clustering**: Apply clustering algorithms like **K-Means**, **DBSCAN**, or **Hierarchical** to group similar customers together.
3. **Cluster Evaluation**: Evaluate the clusters using the **DB Index** and visualize the results.

### Files:
- `customer_segmentation_notebook.ipynb`: Jupyter notebook with the implementation of clustering and evaluation.
- `customer_segmentation_report.pdf`: PDF report with cluster evaluation and analysis.

## Requirements

The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

Install the required dependencies by running:


## How to Run the Code

1. Clone the repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open the corresponding Jupyter notebooks for each task (`Task1_EDA/eda_notebook.ipynb`, `Task2_Lookalike_Model/lookalike_model_notebook.ipynb`, `Task3_Customer_Segmentation/customer_segmentation_notebook.ipynb`).
4. Execute the cells sequentially to run the analysis and generate results.

## Business Impact

This project provides valuable insights into customer behavior, identifies similar customers for targeted marketing, and segments customers for better personalization strategies. The insights can guide business decisions to improve sales, customer engagement, and retention.

## License

This project is licensed under the MIT License.
