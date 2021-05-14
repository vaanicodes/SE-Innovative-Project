# SE-Innovative-Project

### Installation

1. Clone the `psychopathology-fer-assistant` repo:
```bash
git clone https://github.com/vaanicodes/SE-Innovative-Project.git
```
2. Create a virtual environment with Python 3.7. (For this step I will assume that you are able to create a virtual environment with `virtualenv` or `conda`, but in any case you can check [Real Python's post about virtual environments](https://realpython.com/python-virtual-environments-a-primer/).)
3. Install requirements using `pip`:
```bash
pip install -r requirements.txt
```
4. You may also need to create your own real-time database on Firebase and set the corresponding configuration variables on the `app/__init__.py` and `rpi/main.py` files.

### Run the dashboard

To run the dashboard you will need to get access to the MongoDB cluster by setting the `MONGO_URI` variable in the corresponding `db` file. Once you have done this and have installed the requirements, get the dashboard up and running with:
```bash
python run.py
```
