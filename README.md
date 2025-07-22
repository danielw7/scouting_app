# ⚽ Football Scouting App (can be adapted to any sports)

This is an interactive R Shiny application for evaluating football player transfers and do scouting. It allows users to assess potential success of player-club transfers based on customizable criteria and visualize player profiles using radar charts.

## 🚀 Features

- Rate players across multiple dimensions (General, Position, Club) using sliders
- Save and edit player-club transfer evaluations
- Normalize ratings to generate consistent scores
- Compare up to 4 players using radar plots with performance color cues
- Export radar plots as high-resolution images
- Visualize and export a scatterplot with projected fit vs. projected fee
- Tooltips to explain rating scales
- Responsive, tab-based layout:
  - **Player Rating**: Input and save ratings
  - **Overview Table**: View and edit all entries
  - **Visualizations**: Radar plots and comparisons

## 🛠️ How to Run the App

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/football-scouting-app.git
   cd football-scouting-app
2. Install required R packages
   ```bash
   install.packages(c("shiny", "shinydashboard", "fmsb", "shinyBS", "DT", "shinyWidgets", "shinyscreenshot"))
4. Run the app in R or RStudio
   ```bash
   shiny::runApp()

## To Do / Improvements
- Enable rating of clubs or coaches
- Export full player database

## File structure
   ```bash
    ├── app.R                # Main Shiny app
    ├── player_data.csv      # Stored ratings (auto-created if not present)
    ├── README.md
    └── www/
        └── custom.css       # Optional styling (e.g., tooltip width)
