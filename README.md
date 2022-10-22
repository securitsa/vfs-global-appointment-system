
By default, it runs every 2 minutes and check for visa slots at VFS website and notifies the user by SMS and call <br/>
The interval can be changed in the config.

## How to use
1. Clone the repo
2. Move into the repo: `cd vfs_appointment_bot` <br/>
3. Update the config file (`config/config.ini`) with VFS and Twilio credentials
3. Create a new virtual environment: `python3 -m venv venv` <br/>
4. Activate the environment (might differ a bit for windows and MacOS): `source venv/bin/activate` <br/>
5. Install the dependencies: `pip install -r requirements.txt` <br/>
6. Run the script: 

`python vfs_appointment_bot/vfs_appointment_bot.py '<vfs_centre>' '<visa_category>' '<visa_subcategory>'`

OR

`python vfs_appointment_bot/vfs_appointment_bot.py`

