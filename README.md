# Research

```mermaid
graph TD
    A[1. Research Design & Approach] --> B(1.1. Data Collection);
    B --> C{Survey Design};
    B --> D{Sampling Method (Convenience)};
    B --> E{Sample Size ([Number])};
    B --> F{Variables (Speed, Communication, Quality, Complexity)};

    F -- Measured With & Without AI --> G(Data Points);

    G --> H[2. Data Processing & Cleaning];
    H --> I(2.1. Data Preparation);
    I --> J{Variables Included (List)};
    I --> K{Data Cleaning (Missing Values, Outliers)};
    H --> L(2.2. Recoding & Transformation);
    L --> M{Recoding Categorical Variables};
    L --> N{Composite Score Calculation (Speed, Collaboration, Quality, Complexity)};

    N --> O[3. Data Analysis];
    O --> P(3.1. Descriptive Statistics);
    P --> Q{Mean, Median, SD (Table)};
    P --> R{Frequency & Cross-tabulation (Bar Chart)};
    O --> S(3.2. Correlation Analysis);
    S --> T{Pearson Correlation (Table, Scatter Plot)};
    O --> U(3.3. Comparative Analysis);
    U --> V{Paired Samples T-Test (Table, Box Plot)};
    U --> W{Independent Samples T-Test (Table, Box Plot)};

    N --> X[4. Constructing Composite Scores];
    X --> Y(4.1. Composite Score Calculation);
    X --> Z(4.2. Validity & Reliability Testing);
    Z --> AA{Cronbach's Alpha (Table)};

    O --> BB[5. Hypothesis Testing];
    BB --> CC(5.1. Hypotheses (H1-H4));
    BB --> DD(5.2. Statistical Tests (T-Tests, ANOVA));
    DD --> EE{Hypothesis Test Results (Table)};

    O --> FF[6. Data Visualization];
    FF --> GG(6.1. Graphs & Charts (Bar, Box, Scatter));
    FF --> HH(6.2. Tables (Summary Tables));

    EE --> II[7. Interpretation & Reporting];
    II --> JJ(7.1. Analysis of Results);
    II --> KK(7.2. Conclusion & Implications);
