# UCT 3rd Year Project: ATLAS Open Data – WZ Search

This repository contains a Jupyter Notebook for a UCT 3rd Year Physics Project, where students analyse real ATLAS Open Data to search for evidence of W and Z bosons.

## Prerequisites

Before running the notebook, ensure you have the following installed:

- Python 3.8 or later (Python 3.10 recommended)  
- Jupyter Notebook  

---

## Clone the repository

Clone this repository:
   ```bash
   git clone https://github.com/drkevinbarends/wz_search.git
   cd wz_search
   ```

---

## Open a Virtual Environment

Create a virtual environment to avoid interfering with your existing setup:

```bash
python -m venv .env
```

Activate the environment. If you have Linux or MAC:
```bash
source .env/bin/activate
```

If you have Windows:
```bash
.env/bin/Activate.ps1
```

## Installation

Install the required Python libraries using the `./utils/requirements.txt` file:
```bash
pip install -r ./utils/requirements.txt
```

## Download the data files 

The data sits in a dataset folder on Sharepoint. That folder contains two subfolders called data and simulation. Download everything as is and the data needs to be store as is, under datasets, under data and simulation.
   
The project requires input data files that can be downloaded from the following link: [Data Files](https://uctcloud-my.sharepoint.com/:f:/r/personal/01452979_wf_uct_ac_za/Documents/PHY3%20Projects/wz_search?csf=1&web=1&e=aOyZUZ).

## Contribution

Contributions are welcome. Feel free to submit pull requests or open issues.

## License

This repository is for educational purposes and follows the licensing terms of ATLAS Open Data.
