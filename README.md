# 🏀 NBA MVP Predictor

A machine learning project that predicts NBA Most Valuable Player (MVP) winners using historical player statistics and advanced analytics. This project analyzes historical NBA data to identify patterns and key performance indicators that contribute to MVP selection.

## 📊 Features

- Historical NBA player statistics analysis
- Data cleaning and preprocessing pipeline
- MVP prediction model using machine learning
- Player performance visualization and comparison
- Season-by-season MVP probability tracking

## 📁 Project Structure

```
NBA_MVP_Predictor/
├── notebooks/           # Jupyter notebooks for analysis and modeling
├── src/                # Source code for the MVP prediction model
├── data/               # Raw and processed NBA statistics
├── headshots/          # Player profile images
└── README.md
```

## 🔢 Data Sources

The project utilizes the following datasets:
- `NBA_all_seasons_combined_cleaned_stats.csv`: Cleaned and processed player statistics including:
  - Traditional stats (points, rebounds, assists, etc.)
  - Advanced metrics (PER, Win Shares, etc.)
  - Team performance indicators
- `NBA_all_seasons_combined_stats_wrong.csv`: Raw data before cleaning and preprocessing

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook/Lab
- Required Python packages (to be listed in requirements.txt)

### Installation

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/NBA_MVP_Predictor.git
cd NBA_MVP_Predictor
```

2. Set up a virtual environment (recommended)
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. Install dependencies (once requirements.txt is added)
```bash
pip install -r requirements.txt
```

## 📈 Usage

1. Open the Jupyter notebooks in the `notebooks/` directory to:
   - Explore the data analysis process
   - View model development and training
   - See prediction results and evaluations

2. Use the scripts in `src/` to:
   - Process new NBA statistics data
   - Make MVP predictions for current season
   - Analyze player performance trends

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.


## 📧 Contact

Feel free to reach out with questions or suggestions!
