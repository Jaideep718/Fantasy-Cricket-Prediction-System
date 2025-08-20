## Overview

This notebook automates the process of:

- Extracting playing XI from an Excel file
- Scraping player stats (batting, bowling, fielding) from ESPN Cricinfo
- Predicting future performance using linear regression
- Calculating Dream11 scores for each player
- Selecting an optimal Dream11 team based on predicted scores

## Features

- Uses pandas, requests, BeautifulSoup, scikit-learn, and numpy
- Handles missing/invalid data gracefully
- Predicts key stats: runs, wickets, strike rate, economy, catches, stumpings, etc.
- Outputs final team with captain/vice-captain selection
- Saves results to CSV

## How to Use

1. Place your squad Excel file (e.g., `SquadPlayerNames_IndianT20League.xlsx`) in the same directory.
2. Set the desired match number in the notebook.
3. Run all cells in order.
4. The notebook will print the predicted stats, Dream11 scores, and the selected team.
5. Results are saved to `CricTensors_Output.csv`.

## Requirements

- Python 3.x
- pandas
- requests
- beautifulsoup4
- scikit-learn
- numpy

Install dependencies with:

```powershell
pip install pandas requests beautifulsoup4 scikit-learn numpy
```

## Output

- Predicted stats for each player
- Dream11 scores
- Final team selection (with captain and vice-captain)
- CSV file with results

## License

MIT

## Credits

Built by [Reddy Jaideep](https://github.com/Jaideep718).
