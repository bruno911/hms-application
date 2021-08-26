
## Create Virtual Environment and install dependencies.


`python3.7 -m virtualenv ~/python-venvs/hms-framework`


## Install dependencies
`source ~/python-venvs/hms-framework`
`python -m pip install -r requirements.txt`

# Start a new "Hotel"

1. Copy the requirements.txt into a new project.
2. Create virtualenv
3. Initialize virtualenv
4. Install new django app, usually hotel name:
`django-admin startproject hms_kerry_center_hotel` (note underscore in project name it is required by Django.)
5. Copy settings.py into new project
6. Adapt settings.py to suit the new hotel, extend classes when necessary