# AllegroAPI

Python 3 wrapper for Allegro API. We found out that Allegro documentation is poor and badly written, examples are only in Python 2 version and some of them are not working anymore.


# Requirements:
python 3

<b>packages:</b> <br />
API only: <br />
  client <br />
  suds-py3 <br />

<b>Records:</b> <br />
  pandas <br />
  pickle <br />
  datetime <br />
  os <br />



<b> API requirements: </b><br />
Allegro WebAPI key - Required for everything. <br />
Allegro login - some functionalities will work without it. <br />
Allegro password - some functionalities will work without it. <br />


# Files:
<b>AllegroQuerry.py: </b><br />
Library sends requests to Allegro example of usage in file. User needs to specify filterOptions, every option for filters is returned in response from Allegro.

<b>record.py: </b><br />
This file is just additional library that helps convert Allegro API response to some "Human" data types. 
It is able to convert Allegro response to:<br /> 
Pandas DataFrame<br /> 
string<br /> 
Pickle (save/read) <br />

If you want you can easily add new methods to parse to new datatypes. 
Basically AllegroQuerry.py can work properly without record.py but we recommend it as it was designed from start to be used together.
