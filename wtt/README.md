The file wtt.py is a simple python API to the google.generativeai API.

wtt - bash wrapper around wtt.py


MANUAL

SYNOPSIS wtt the talk

wtt appends junk/data to the output file

Installation 
git clone https://github.com/wttpublicdomain/walkthetalk
cd walkthetalk/wtt
python -m venv venv
. venv/bin/activate
export GOOGLE_API_KEY="your-google-api-key"
export PATH=$PATH:.

Usage
wtt
wtt hello
wtt hello world
wtt any number of strings
wtt file
wtt any number of files
wtt any combination of string and file arguments

Notes:
wtt does not have any options
You can use command substitution syntax $(command)
