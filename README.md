#Starting ner-annotator by Tecoholic using Anaconda prompt
It is anaconda code for starting ner-application created by the author tecoholic
Clone the repository or download zip file from techolic ner-annotator
This command is specifically for Anaconda users.

>>cd C:\ner-annotator-main

>>conda create -n venv python

>>conda activate venv

install the requirements using the following command
>>conda install -n venv requirements.txt

If the installation fails, individually install each dependencies. If the individual installation fails, use conda-forge
>>conda install -c conda-forge regex==2020.10.28

>>python annotator/server.py

In a different terminal
>>cd C:\ner-annotator-main\ui
>>
>>conda install yarn
>>
>>yarn install
>>
>>yarn serve
