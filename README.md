# FakeNewsDetection

### Enviroment Configuration
* Use the requirements.txt file to create a virtual enviroment
  * `python -m venv FakeNewsEnv`
  * `python3 -m pip install -r requirements.txt`
* Replace the `FakeNewsDetection/FakeNewsEnv/lib/python3.8/site-packages/nlpaug/augmenter/word/synonym.py` file with the one included in this repository. 


## Progress Log
3/26/21
* Got nlpaug package working. Before running code, make sure to create virtual enviroment "FakeNewsEnv" (or some other name) using the "requirements.txt" file. 
* Organized the files used for the neural networked into a directory. Also organized the .csv files within that into a subdirectory. 


3/27/21
* Modified nlpaug to only exchange adjectives with synonyms.
* Did more organization, attempted to disambiguate filepaths.
