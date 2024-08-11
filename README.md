# A/B Testing Analysis for Math and Statistics Course – Hyper Island

## Overview

This repository contains two Jupyter notebooks that demonstrate A/B testing analyses, developed as part of the Math and Statistics course at Hyper Island. These notebooks provide a practical, hands-on learning experience in A/B testing methodologies and statistical analysis. The scenarios and data are fictional, designed to simulate real-world applications in both e-commerce and pharmaceutical research.

## Repository Structure

- **DA25_math_assessment.ipynb**: Jupyter notebook for the Cooking Website A/B Test.
- **assessment_da25.csv**: Dataset used for the Cooking Website A/B Test.
- **DA25_math_assessment_pwd.ipynb**: Jupyter notebook for the Pharmaceutical Company A/B Test, with data generated randomly.

## Notebooks

### 1. **Cooking Website A/B Test (DA25_math_assessment.ipynb)**

This notebook simulates an A/B test conducted on a cooking website to compare two different product page layouts:
- **Variant A**: Traditional horizontal layout for product images.
- **Variant B**: New vertical layout for product images.

**Key Metrics Analyzed**:
- **Add-to-Cart Rate**: Percentage of users who add items to their cart.
- **Clicks on Media**: User engagement with media elements on the product page.
- **Cart Abandonment Rate**: Percentage of users who add items to their cart but do not complete the purchase.
- **Gross Merchandise Value (GMV)**: Total sales revenue generated during the test period.
- **Purchases per User**: Average number of purchases per user in each variant group.

**Dataset**: The analysis is based on the data provided in `assessment_da25.csv`.

The objective is to determine which layout (horizontal or vertical) improves user engagement and conversion rates.

### 2. **Pharmaceutical Company A/B Test (DA25_math_assessment_pwd.ipynb)**

This notebook presents a hypothetical A/B test scenario for a pharmaceutical company, comparing a new diabetes medication (Treatment group) with the current leading medication (Control group).

**Key Metrics Analyzed**:
- **Efficacy in Blood Sugar Level Management**: How well each medication controls blood sugar levels over a specific period.
- **Incidence of Side Effects**: Frequency and severity of side effects reported in each group.

**Data Generation**: The data for this analysis was generated randomly to simulate a real-world scenario.

The objective is to evaluate whether the new medication offers better efficacy and a preferable side-effect profile compared to the existing treatment.

## Objective

The primary goal of these notebooks is to provide a practical framework for conducting A/B tests and applying statistical analysis techniques. By working through these examples, students will:
- Gain a deeper understanding of A/B testing methodologies.
- Learn how to apply statistical tools to real-world business and pharmaceutical scenarios.
- Develop the ability to make data-driven decisions based on experimental results.

## How to Use

To use the notebooks and explore the analyses:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/ilazan/AB-testing.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd AB-testing
    ```
3. **Open the Jupyter Notebooks**:
    - Launch Jupyter Notebook:
      ```bash
      jupyter notebook
      ```
    - Open `DA25_math_assessment.ipynb` to explore the Cooking Website A/B Test.
    - Open `DA25_math_assessment_pwd.ipynb` to explore the Pharmaceutical Company A/B Test.

## Data

**Disclaimer**: All data used in these notebooks are fictional and created solely for educational purposes. The data set `assessment_da25.csv` is designed to simulate real-world e-commerce scenarios, and the data in the pharmaceutical test was generated randomly to mimic clinical trial conditions.

## Contributing

We welcome contributions to this repository. To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Special thanks to [Hyper Island](https://www.hyperisland.com) and Alizé Papp for providing the educational framework that inspired this project.
- Thanks to the open-source community for tools and resources that facilitated this work.
