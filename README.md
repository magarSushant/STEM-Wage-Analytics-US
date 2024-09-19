# STEM-Wage-Analytics-US
Comprehensive analysis of wage trends across STEM and Non-STEM occupations in the US, using data from the Bureau of Labor Statistics. Predictive modeling and insights for regional economic and workforce development.
# STEM Occupation Wage Analytics

## Comprehensive Review of Wage Trends Across the United States

### Project Overview

This project is a detailed examination of wage trends across STEM (Science, Technology, Engineering, Mathematics) and Non-STEM occupations, using data from the U.S. Bureau of Labor Statistics. The analysis focuses on wage disparities across Metropolitan Statistical Areas (MSAs), highlighting regional variations and the impact of economic factors such as GDP growth and inflation. The project leverages Alteryx for data processing, blending, and advanced predictive modeling to provide actionable insights for policymakers, educational institutions, and industry stakeholders.

### Context and Objectives

This project aims to:
- **Analyze wage trends** between STEM and Non-STEM occupations across diverse regions.
- **Examine regional disparities** in wages and employment, identifying key factors that contribute to these differences.
- **Predict wage trends** using machine learning models, providing foresight for policy and educational strategies.
- **Recommend interventions** for economic development and workforce optimization, with a focus on STEM occupations.

### Data Processing and Preparation

The dataset includes detailed information such as area statistics, industry details, occupational data, employment figures, and wage data. Key steps in the data preparation process include:
- **Data Cleaning**: Removing fields with significant null values (e.g., JOBS_1000, LOC_QUOTIENT) to enhance data integrity.
- **Data Transformation**: Converting relevant fields from string to numeric values for accurate analysis.
- **Data Blending**: Integrating STEM-specific occupation codes using a lookup dataset to efficiently categorize occupations as STEM or Non-STEM.
- **Handling Null Values**: Filtering out incomplete rows in crucial fields (e.g., TOT_EMP) to ensure the reliability of statistical analyses and visualizations.

### Methodological Approach

This analysis adopts a multi-layered approach to provide both a holistic and granular view of wage dynamics:

1. **Holistic STEM vs. Non-STEM Analysis**: A broad comparative analysis of wage trends between STEM and Non-STEM occupations, focusing on regional economic impacts.
2. **Descriptive Analytics**: Using Alteryx tools, wage distribution was analyzed across MSAs, with particular attention to variations influenced by educational attainment.
3. **Cross-Industry Data**: A methodologically important decision was the inclusion of cross-industry data to provide a comprehensive view of employment trends, reflecting the intersection of STEM roles across multiple sectors.
4. **Granular Descriptive Analytics**: Detailed wage analysis was conducted within MSAs, leveraging SOC codes and education-related data to assess wage trends based on degree levels.

### Predictive Modeling

To forecast wage trends, a combination of predictive models was employed:
- **Linear Regression**: For analyzing straightforward relationships between variables like education and wages.
- **Decision Trees**: To identify complex, non-linear relationships and key wage determinants.
- **Random Forests**: Providing robustness by aggregating decision trees to enhance prediction accuracy, especially in large datasets.

### Key Findings
- **STEM Wage Premium**: STEM occupations consistently exhibit higher wages than Non-STEM roles across all regions.
- **Regional Disparities**: Significant wage and employment discrepancies exist across MSAs, underscoring the need for targeted interventions, particularly in lower-wage areas.
- **Educational Impact**: Higher educational attainment correlates positively with higher wages in STEM fields.
- **Economic Indicators**: Inflation rates and GDP growth are critical factors in predicting wage trends, reflecting broader macroeconomic conditions.

### Assumptions and Methodological Choices

Throughout the analysis, key decisions were made to ensure accuracy and integrity. Below are the primary assumptions and the corresponding methodological choices:

- **Null Value Handling**:  
  - **Assumption**: Imputing wage data would introduce bias.  
  - **Methodological Choice**: Excluded rows with null values in wage fields (Hourly_Mean, Annual_Mean, etc.) to maintain data reliability.

- **STEM/Non-STEM Classification**:  
  - **Assumption**: Accurate classification of occupations is critical for comparison.  
  - **Methodological Choice**: Used detailed SOC codes for precise classification, employing a Find Replace tool for scalability.

- **Granularity in Data**:  
  - **Assumption**: Detailed occupation codes offer more precision.  
  - **Methodological Choice**: Opted for detailed SOC levels to avoid misclassification and reflect true wage trends.

- **Employment Data Quality**:  
  - **Assumption**: Missing employment data could distort trends.  
  - **Methodological Choice**: Excluded rows with null values in the "TOT_EMP" column for reliable employment analysis.

- **Cross-Industry Inclusion**:  
  - **Assumption**: STEM occupations span multiple industries.  
  - **Methodological Choice**: Integrated cross-industry data to provide a holistic view of STEM wage and employment trends.

- **Education-Wage Link**:  
  - **Assumption**: Education significantly impacts wages.  
  - **Methodological Choice**: Merged wage data with educational levels to analyze wage trends based on degree requirements.

- **Wage Metrics (Mean and Median)**:  
  - **Assumption**: Both mean and median metrics provide valuable insights.  
  - **Methodological Choice**: Used both metrics for a comprehensive wage analysis, accounting for outliers and typical worker earnings.

- **MSA Focus for Analytics**:  
  - **Assumption**: MSAs are economic hubs and ideal for wage analysis.  
  - **Methodological Choice**: Focused on MSAs to analyze wage trends where economic and workforce development are most relevant.

- **Predictive Modeling**:  
  - **Assumption**: Macroeconomic factors influence wage dynamics.  
  - **Methodological Choice**: Incorporated inflation rates and GDP growth into predictive models to improve wage trend forecasting.

- **Data Preparation with Alteryx**:  
  - **Assumption**: Extensive cleaning and preparation are required for accuracy.  
  - **Methodological Choice**: Used Alteryx for data preparation, blending, and modeling, ensuring a clean and robust dataset.

### Technologies Used
- **Alteryx**: For data preparation, cleaning, blending, and predictive modeling.
- **Excel**: For initial data management and exploration.
- **GitHub**: Version control and repository for project materials.

### How to Use This Repository
1. **Alteryx Workflow**: Follow the provided workflow to replicate data cleaning, integration, and predictive modeling steps.
2. **Download and Explore the Data**: Place the appropriate datasets in the designated folders to explore the analysis.
3. **Consult the Final Report**: Review the detailed analysis, findings, and recommendations to gain insights into STEM wage trends.

### Project Resources
- **Final Report (PDF)**: Detailed analysis of wage trends, regional disparities, and strategic recommendations for addressing STEM labor market challenges.
- **Alteryx Workflow**: Annotated workflow demonstrating the methodology used for data preparation, blending, and predictive modeling.
  
### Findings and Strategic Recommendations
The analysis consistently confirmed that STEM jobs offer a wage premium over Non-STEM jobs, driven by factors such as educational attainment and regional economic conditions. Policy recommendations include:
- **Targeted Educational Initiatives**: To promote STEM education in low-employment regions.
- **Economic Development Strategies**: Designed to stimulate job creation and wage growth in lower-wage areas.
- **Workforce Development**: Aligning policies with findings to ensure the availability of high-skilled labor in STEM fields.

### Disclaimer
This project is for academic purposes and does not reflect any real-world consultancy engagement. The data and insights are derived from publicly available U.S. Bureau of Labor Statistics datasets and were analyzed as part of an academic curriculum.
