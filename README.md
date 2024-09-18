# Multivariate Analysis of Glass Dataset
A detailed multivariate analysis of the Glass dataset using correlation analysis, PCA, clustering, LDA, and Random Forest to explore relationships between chemical elements and classify glass types. Includes visualizations and insights into the properties and classification of glass.

### Dataset
Glass Dataset: This dataset includes various chemical elements present in different types of glass. The dataset was used to understand how these elements interact and how they contribute to the properties of the glass.

### Objectives
### Objectives
1. **Correlation Analysis:** Identify high positive, negative, and low/no correlations between the chemical elements to understand their relationships.
2. **Distribution Analysis:** Analyze the distribution of key variables using histograms to understand their spread and central tendencies.
3. **PCA:** Perform Principal Component Analysis to reduce dimensionality and identify key components that explain the most variance in the dataset.
4. **Clustering:** Use hierarchical clustering methods and k-means clustering to identify natural groupings in the data.
5. **LDA and Random Forest:** Apply Linear Discriminant Analysis and Random Forest models to classify glass types and understand feature importance.

### Repository Structure
- `Glass_Analysis.Rmd` - R Markdown file containing the complete analysis of the Glass dataset.
- `Detailed_Report.pdf` - PDF file with the comprehensive report of the analysis.

### Key Findings
1. **Correlation Analysis:** Strong positive correlations were observed, such as between Refractive Index (RI) and Calcium (Ca), while strong negative correlations were noted between Magnesium (Mg) and Barium (Ba). These relationships can guide further understanding of glass properties.
2. **Distribution Patterns:** Various elements showed different distribution patterns. For example, RI showed a roughly normal distribution, while Barium (Ba) exhibited a skewed distribution with many low values.
3. **PCA:** The first few principal components captured most of the variance, indicating that dimensionality reduction is feasible without losing significant information. The PCA biplot helped visualize the influence of each chemical element on the variance.
4. **Clustering:** Hierarchical clustering and k-means clustering revealed natural groupings within the dataset, suggesting the potential for classifying glass types based on their elemental composition.
5. **LDA and Random Forest:** LDA effectively maximized the separation between different glass types, while the Random Forest model identified Magnesium (Mg) and Refractive Index (RI) as critical predictors.

### Conclusion
The analysis of the Glass dataset provides insights into the chemical composition of glass and how these elements contribute to its properties. By applying various statistical methods, the analysis helps in classifying glass types, which can have practical applications in industries like glass manufacturing, recycling, and forensic science.

### How to Use
To reproduce the analysis, clone this repository and open the R Markdown file (`Glass_Analysis.Rmd`). You can knit this file in RStudio to generate the output.
```bash
# Clone the repository
https://github.com/dandyy11/Multivariate-Analysis-of-Glass-Dataset.git

### Contact
For questions or suggestions, please contact Salman Imtiaz at salman.imtiaz414@gmail.com
