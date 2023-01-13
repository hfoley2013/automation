# LAB - Class 19

## Project: Automation of Email and Phone Number Scraping

## Author: Harper Foley

## Links and Resources

* [GitHub Repo](https://github.com/hfoley2013/automation)

## Setup

* To set up this repo create a local repository on your machine
* Create a virtual environment for Python
  * `python3.11 -m venv .venv`
* Activate the venv file
  * `source .venv/bin/activate`
* Install `pytest`
  * This will allow you to run tests on the program
  * `pip install pytest`
* Use `git clone` to clone the repo to your local machine
  * `git clone https://github.com/hfoley2013/automation.git`

## How to initialize/run your application

* To run the application, run `python3.11 modules/automation.py` in the command line
* Before doing so, you can import the text you want to search into the `potential_contacts.txt` file or upload a new file
  * NOTE: If you want to upload a new file, you will need to change the file path for the `with open()` function at the start of the program to reflect the name and location of your uploaded file
* After running the program, the emails and phone numbers inside your document will populate into the `emails.txt` and `phone_numbers.txt` files respectively

## Tests

* How do you run tests?
  * Tests are conducted via `pytest`
  * You may need to specify the location of the tests as follows:
    * `pytest tests/test_automation.py`
* Tests check for the following:
  * We get the number of expected phone numbers: 100
  * We get the number of expected emails: 100
