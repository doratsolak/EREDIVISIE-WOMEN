### Pythagorean Expectation in Eredivisie Women

#### Introduction
This repository analyzes the performance of teams in the Eredivisie Women's league for the 2023-2024 season using the Pythagorean Expectation and Winning Percentage metrics.

#### Pythagorean Expectation
The Pythagorean Expectation formula estimates a team's expected wins based on goals scored and conceded:
Pythagorean Expectation= Goals Scored^2+Goals Conceded^2 / Goals Scored^2

This metric provides insights into a team's efficiency in scoring and preventing goals.

#### Winning Percentage
The winning percentage is calculated as:
Winning Percentage= Number of Wins/ Total Number of Games ×100

It shows the actual percentage of games won by a team.

#### Tools Used
- `pandas` for data manipulation
- `numpy` for numerical operations
- `statsmodels` for statistical models
- `matplotlib` and `seaborn` for data visualization

#### Data
The data covers various statistics including home and away performances for each team, goals scored and conceded, and calculated metrics like Pythagorean Expectation and Winning Percentage.

#### Analysis
The analysis focuses on:
- **Top Teams:** Teams like Twente and Ajax dominating with high Pythagorean Expectations and winning percentages.
- **Mid-Tier Teams:** Teams like PSV and Fortuna Sittard performing solidly but with room for improvement.
- **Lower-Tier Teams:** Teams like VV Alkmaar and Heerenveen needing significant improvements based on low Pythagorean Expectations and winning percentages.

#### Scatter Plot and Correlation Analysis
A scatter plot visualizes the relationship between Pythagorean Expectation and Winning Percentage, providing a clear comparison across teams. Correlation analysis between home and away goals further explores team performance trends.

#### Conclusion
This README provides a comprehensive overview of team performance in the Eredivisie Women's league using statistical metrics and visualizations. It serves as a resource for understanding team dynamics and performance drivers during the 2023-2024 season.

#### Repository Structure
- `README.md`: This file providing an overview of the project.
- `Eredivisie_Pythagorean_Expectation.ipynb`: Jupyter notebook containing code, visualizations, and detailed analysis.
- `EREDIVISIE VROUWEN.xlsx`: Excel file containing the raw data used for analysis.

For detailed code implementation and further insights, refer to the `Eredivisie_Pythagorean_Expectation.ipynb` notebook in this repository.
