# Basketball-Statistics-Analysis-Tool

A Python-based wnba analytics tool for scraping, cleaning, analyzing, and visualizing WNBA player statistics.  
The program automates data collection from [Basketball Reference](https://www.basketball-reference.com), stores results in CSV files. 


# Usage
- To run GUI simply run main.py module
- To update stats from the regular season run list_players_update.py module.

```bash
git clone https://github.com/london-codes/Basketball-Statistics-Analysis-Tool.git
cd Basketball-Statistics-Analysis-Tool
pip install -r requirements.txt
```

# Limitations
- Cannot update all players in the database before running the GUI because of Basketball reference rate limit, as it would significantly increase the time to open the application. Instead of this, User must run the list_player_update.py module to update all the players in the database.


