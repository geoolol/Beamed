
# Q&A 
- Q: **`Getting errors on running install.bat file`**
- A: Just run the error remover.bat file as it should allow for all modules to be installed correctly
- Q: **`SSL Certificate Error`**
- A: Just install [CRT File](https://crt.sh/?id=2835394). Then run it and install. (This is common and it was a certificate that expired May 30th 2020. But a new one came out so install it.). If you wanna go into further detail then head to [SITE](https://support.sectigo.com/Com_KnowledgeDetailPage?Id=kA03l00000117LT).  
- Q: **`Module Missing`**
- A: Just run `pip install -r requirements.txt` in console. This insures that all modules required for Alucard are installed and up to date!
- Q: **`Windll not found`**
- A: Beamed uses some windows features from modules. Example windll from ctypes. windll is used to add the console title. You can remove the title setters in-order to fix it.
- Q: **`TypeError: __new__() got an unexpected keyword argument 'deny_new'`**
- A: This error occured on an old installation of discord.py to fix simply run :`pip install -U discord.py` this updates discord.py!
- Q: **`Cannot run the file even though the batch files gave no errors`**
- A: Install Python from the microsoft store and run the file through cmd with the command 'python Beamed.py' whilst in the Beamed directory, but make sure you have python 3.8
- Q: **`IP lookup fails`**
- A: Create an account on https://extreme-ip-lookup.com and get a key to put in the config file

Any other errors message me on discord: `geo#3000`
