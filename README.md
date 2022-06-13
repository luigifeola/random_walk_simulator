# Random Walk Simulator
## Requirements
To be able to run information-market, you must have:
- A recent version of Linux, MacOSX or Windows
- **Python** 3.6 or newer
## Installation
First clone the git repository into a given folder on your computer:
```bash
git clone https://github.com/luigifeola/random_walk_simulator.git
```
Then, navigate into the newly created folder, create a new python virtual environment and install the required python packages:
```bash
cd random_walk_simulator
python -m venv rw-env
source rw-env/bin/activate
pip install -r requirements.txt
```
## Run
First, edit the _config.txt_ file inside the config folder with the parameters you want to use. Then, to run random_walk_simulator, simply open a terminal, cd to the src folder and run the program.
```bash
cd path/to/src
python .py ../config/config.txt
```

