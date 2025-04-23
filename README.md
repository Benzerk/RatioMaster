# Ratio.py

Ratio.py is a small command line RatioMaster.Net like in Python3. It fakes upload stats of a torrent. 
Current emulators available are:
* qBitorrent/5.0.5

## Requirements
Python 3.x
```bash
python -m pip install --upgrade pip
python -m venv .venv
source .venv/Scripts/Activate
pip install -r requirements.txt
```

## Usage
```bash
source .venv/Scripts/Activate
python ratio.py -c configuration.json 
```

## Configuration example
```json
{
   "torrent": "<Torrent file path>",
   "upload": "<Upload speed (kB/s)>"
}
```

