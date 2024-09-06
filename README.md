# Hotel-Reviews-Analysis
This Jupyter Notebook provides a comprehensive analysis of Highfield Private Hotel reviews, aiming to gain insights into guest satisfaction and identify areas for improvement.

### **Data**
The analysis is based on a CSV file containing hotel reviews, with columns such as:

* `Review date`
* `Guest name`
* `Reservation number`
* `Review title`
* `Positive review`
* `Negative review`
* `Review score`
* `Staff`
* `Cleanliness`
* `Location`
* `Facilities`
* `Comfort`
* `Value for money`
* `Property reply`

### **Libraries Used**
* **pandas:** For data manipulation and analysis.
* **matplotlib:** For creating static plots.
* **seaborn:** For statistical data visualization.
* **wordcloud:** For generating word clouds.
* **textblob:** For sentiment analysis.

### **Analysis Steps**
1. **Data Loading:** Loads the CSV file into a pandas DataFrame.
2. **Data Exploration:** Provides a basic overview of the data, including summary statistics and data types.
3. **Data Cleaning:** Handles missing values and converts data types as needed.
4. **Review Score Analysis:** Analyzes the distribution of review scores and calculates the average score.
5. **Positive and Negative Reviews:** Extracts positive and negative reviews and generates word clouds to visualize common terms.
6. **Sentiment Analysis:** Calculates sentiment polarity and subjectivity for positive reviews.
7. **Correlation Analysis:** Examines correlations between review scores and other aspects of the hotel.

### **Usage**
1. **Install required libraries:**
   ```bash
   pip install pandas matplotlib seaborn wordcloud textblob
   ```
2. **Replace the filename:** In the notebook, replace `reviews.csv'` with the actual path to your CSV file.
3. **Run the cells:** Execute the cells in the notebook to perform the analysis and generate visualizations.

### **Screenshot**

[](img.png)
