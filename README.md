# progressBars

INSTALLATION:
1. Download ZIP and extract to your FXServer resources folder.
2. Make sure folder is called progressBars
3. add `ensure progressBars` to your server.cfg

USAGE:
1. Add `exports['progressBars']:startUI(time, "text")` to whatever functions you want.
   e.g. `exports['progressBars']:startUI(30000, "Starting a fire...")`
