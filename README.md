# Football Players Analysis - FIFA 21: Overview
This project takes a dataset of FIFA 21 player information and aims to look at the relationship and distributions of certain player statistics. The analysis looks at a player's age, nationality, FIFA rating, and FIFA potential rating, and searches for any patterns that emerge within the distributions and correlations between them.

## Objectives
1. **What is the relationship between a player's rating and potential, and is there a siginifant difference between the two between younger and older players?**
   - Determine the correlation between rating and potential rating grouped by age.
   - Assess how significant the difference between the two is between younger and older players.
2. **What is the rating distribution and variance among positions?**
   - Visualise the distribution of a players ratings for each position.
   - Summarise the key differences in rating variance between posititons.
3. **What is the age distribution and variance among position?**
   - Investigate how varied and spread out player ages are, grouped by player position.
   - Determine whether there are any meangingful distinctions between the groups.
4. **Do certain positions peak in rating at older ages compared to other positions?**
   - Plot the relationship of player rating vs age for each position.
   - Investigate the results and see at what age certain positions peak in rating, and compare between positions.
5. **How does the distribution of rating between nationalities differ from that of the distribution of potential of wonderkids (players with high potential at a younger age) between nationalities?**
   - Compare rating variance grouped by nationality to potential rating variance grouped by nationality.
   - Asses whether certain nationalities produce more young talent than other, and if other nationalities have a greater proportion of older higher rated players.
  
## Key insights (Summary)
> For full results, visualisations, and detailed discussion, open the Jupyter notebook FIFA-21.ipynb in this repository.
- Dropped unneccessary columns, as well as renamed and created new useful columns, using ```pandas```.
- Visualised player statistic patterns using ```matplotlib``` and ```seaborn```. For example:
  - **Scatter plots**: Comparing rating to potential rating.
  - **Histograms**: Plotting age and rating distribution.
  - **Line plot**: Visualising relationship between age and rating.
  - **Box plot**: Exploring the difference in rating and potential rating variance across all nationalities.
- Aggregated average values grouped by certain varaibles to better understand the variation between said variables.
- Used Mann-Whitney U tests to determine a significant difference between findings.

## Tools and Libraries
| Purpose | Libraries Used |
|----------|----------------|
| Data manipulation | `pandas`, `numpy` |
| Statistical testing | `scipy.stats (mannwhitneyu)` |
| Data visualization | `matplotlib`, `seaborn`, `math` |

## Installation
1. **Clone this repository**
   ```bash
   git clone https://github.com/lloydy-92/FIFA-21-Analysis.git
   cd FIFA-21-Analysis
2. **(Optional) Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate       # On Windows use: venv\Scripts\activate
3. **Install dependencies**
   ```bash
   pip install pandas numpy scipy matplotlib seaborn math jupyter
4. **Launch the notebook**
   ```bash
   jupyter notebook FIFA-21.ipynb

## Project Structure
```bash
FIFA-21-Analysis/
├── FIFA-21.ipynb        # Main analysis notebook
├── FIFA-21-Complete.csv      # Dataset containing FIFA 21 player information and statistics
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## Contributing
Contributions, suggestions, and improvements are welcome and encouraged! If you would like the enhance any aspect of the project, such as analysis or visualisations:
1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/improve-analysis
3. Commit your changes
   ```bash
   git commit -m 'Add new visualisation'
4. Push to the branch
   ```bash
   git push origin feature/improve-analysis
5. Open a Pull Request

## Author
**Sam Lloyd**, sammy.lloyd@live.com, *github.com/lloydy-92*

## Acknowledgements
- Aayush Mishra on Kaggle for providing the dataset (*https://www.kaggle.com/datasets/aayushmishra1512/fifa-2021-complete-player-data/data*)
- Codecademy Data Science Path for providing structured guidance on this project.
- The open-source community for libraries like ```pandas```, ```matplotlib```, and ```seaborn```.
     
