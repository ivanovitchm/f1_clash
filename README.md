# F1 Clash Game Analysis
# Race Legends


This repository provides data analysis tools to optimize player performance in the F1 Clash game. Utilizing the power of Python and Pandas, our scripts analyze various in-game parameters to give players the edge they need to win.

## Contents

- `F1_Clash_Loadouts.ipynb`: Main script for analyzing driver, car, and boost data.
- `loadout.csv`: Output file containing combined car and boost data.
- `drivers.csv`: Output file containing combined driver and boost data.

## Features

- **Data Combiner**: Combine different game datasets to view synergies between different game components.
- **Performance Limiter**: Ensures in-game attributes do not exceed game-defined limits, providing realistic and applicable results.
- **CSV Export**: Allows users to export the combined data for easy sharing and further analysis.

## How to Use

1. Clone the repository.
2. Input your driver, car, and boost data in the format provided in `F1_Clash_Loadouts.ipynb`.
3. Run `F1_Clash_Loadouts.ipynb`.
4. Check `loadout.csv` and `drivers.csv` for the results.

## Data Format

- `df_drivers`: Contains the performance attributes of different drivers.
- `df_car`: Contains the performance attributes of various cars.
- `df_bottle`: Represents the boosts that can be used in-game.

Each of these datasets needs to be formatted correctly (as shown in `F1_Clash_Loadouts.ipynb`) for the scripts to work as intended.

## Contributions

Contributions are welcome! If you have ideas on how to improve the analysis or find any bugs, please open an issue or submit a pull request.

## Disclaimer

This tool is meant for educational purposes and personal use only. We are not affiliated with the creators of the F1 Clash game.
