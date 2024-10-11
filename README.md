
# NHL Shot Statistics: The Effect of Defending Ice Time on Expected Goals and Shot Outcomes

## Author
- Connor Raney

## Published
- April 28, 2024

## Introduction
This project examines NHL shot data to analyze the influence of defensive ice time on offensive shot outcomes, specifically expected goals (xGoals). Utilizing data from Moneypuck, this analysis includes over 238,304 shots from the 2022-2023 and 2023-2024 NHL seasons. The primary question explores whether the amount of time a defensive team has been on the ice affects the offensive team's ability to generate scoring opportunities.

## Data Source
All data utilized in this project is available for download at Moneypuck, covering detailed shot data from 2007 through the current season, updated nightly. The specific datasets used here encompass only the latest two seasons due to computational constraints. 
- **Data Link**: [Moneypuck Data](https://moneypuck.com/data.htm)

## Repository Contents
- **Data Dictionary**: Description of each of the 124 attributes recorded for every shot, such as player and goalie details, shot angles, distances, and outcomes.
- **Analysis Scripts**: Quarto/ R Markdown files detailing the import, cleaning, visualization, and statistical analysis of the dataset.
- **HTML Output**: An HTML output view of the project, with all graphs, charts, and analysis done, and can be viewed without any work needing to be done to reproduce the results. 

## Key Analyses
1. **Data Cleaning and Preparation**: Importing, merging, and preparing shot data from the 2022-2023 and 2023-2024 seasons.
2. **Visualizations**: Graphical representations of relationships between variables like defending team ice time and expected goals.
3. **Statistical Analysis**:
   - Linear and Logistic Regressions to explore the effect of ice time on shot outcomes.
   - Propensity Score Matching to balance the dataset and mitigate confounding variables.

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/cbrane/qtmfinalproject/
   ```
2. Download the 2022-2023 and 2023-2024 data files from Moneypuck: https://moneypuck.com/data.htm
3. Open and run the QMD/ R Markdown files in an R environment to reproduce the analysis.

## Dependencies
- R
- Libraries: `dplyr`, `ggplot2`, `modelsummary`, `MatchIt`

## Contributing
Feedback and contributions are welcome via pull requests. Please adhere to this project's `code of conduct`.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
- **Connor Raney**
- **Email**: [connor@connorraney.com](mailto:connor@connorraney.com)
- **LinkedIn**: [Connor Raney](https://www.linkedin.com/in/connorraney)

## Acknowledgements
- [Moneypuck.com](https://moneypuck.com/) for providing extensive and detailed NHL shot data.
- Contributors to the NHL API and ESPN for data collection methods.
