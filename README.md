# Gene Expression Data Explorer

This is an R Shiny app designed for exploring gene expression data. It allows users to upload a dataset, filter genes by expression level, and visualize the data using heatmaps and boxplots.

## Features
- **File Upload**: Upload a CSV file containing gene expression data.
- **Heatmap**: Visualize gene expression patterns across selected samples.
- **Boxplot**: Explore expression levels of individual genes.
- **Filtering**: Filter genes by average expression level.
- **Interactive Table**: Display filtered data in a searchable table.

## How to Use
1. Upload a Dataset - 
   - The app accepts CSV files with genes as rows and samples as columns.
   - Example dataset:
     ```csv
     Gene,Sample1,Sample2,Sample3
     Gene1,10,15,20
     Gene2,5,10,15
     Gene3,20,25,30
     ```

2. Filter Genes - 
   - Use the slider to filter genes by average expression level.

3. Select Samples - 
   - Choose samples to include in the heatmap.

4. Select a Gene - 
   - Choose a gene to visualize its expression across samples using a boxplot.

5. View Outputs - 
   - The heatmap and boxplot are displayed in the main panel.
   - The filtered data table is displayed below the plots.

## How to Run the App
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/PriyankaItagi/Gene-Expression.git
2. Open the app.R file in RStudio or your preferred R environment.

3. Install the required R packages if you don't already have them:

R
Copy
install.packages("shiny")
install.packages("ggplot2")
install.packages("pheatmap")
install.packages("DT")
4. Run the app:

In RStudio, click the Run App button.

Alternatively, run the following command in the R console:

R
Copy
shiny::runApp("path/to/your/app.R")
