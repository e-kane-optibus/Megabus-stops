# Megabus-stops

## Purpose
This script removes all stops from stops.txt that are not present stop_times.txt. All stations (which are not present in stops_times.txt) are maintained in the new file.   

## Usage
Tested with Python 3.9.<br>
```python megabus-stops.py feed.zip```<br>
Adjusted stops_txt file is exported to the current directory, after which it can be manually added to the feed's .zip file.<br>

