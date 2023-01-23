For the wrappers of the GoScout Project

Set up like:<br>
├── Drone<br>
│   ├── Drone Execution Functions<br>
│   ├── Drone Main<br>
├── Rover<br>
│   ├── Rover Execution Functions<br>
│   ├── Rover Main<br>
├── Coms<br>
│   ├── Communication Functions<br>
└── .gitignore

To clone correctly:
- git clone ( https://github.com/GoScoutOrg/GoScout.git || git@github.com:GoScoutOrg/GoScout.git )
- cd GoScout
- git submodule update --init

To initialize library dependencies:
- For each subfolder:
    - $ cd ${subfolder}
    - $ python3 -m venv .venv
    - $ source .venv/bin/activate
    - $ pip install -r requirements.txt
**TO EXIT: $ deactivate**
