This Jupyter notebook takes CSV versions of Spotify data and converts them to daily CSV and MD files.

If the Spotify data contains listening data for 300 separate days, for example, this script will output 300 CSV files and 300 MD files with the filename formats YYYY-MM-DD.csv and YYYY-MM-DD.md

This uses a .env file to store path_input (where your Spotify CSV files are located) and path_output (where you want the CSV and MD files written).

Either create a .env file with those paths, or modify cell 2 to include the paths directly.
