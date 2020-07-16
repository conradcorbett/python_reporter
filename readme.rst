Python Reporter
###############

"As-built" documentation script for use with Nutanix **Prism Central** 5.5.0.6 or later.

Use a python virtual environment to run the script. Requires python3.

# Setup your virtual environment in python_reporter directory
python3 -m venv my_venv
source my_venv/bin/activate

# Install packages
which pip
pip list
pip install -e /path/to/setup.py/directory

# Run script
python /full/path/to/python_reporter.py -u <username> -p <password> <pc_ip>

# Deactivate virtual environment
deactivate
rm -rf my_venv