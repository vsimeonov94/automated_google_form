# automated_google_form

Written with python3 and Ansible. Autofill text fields based on their name, radio buttons and check boxes.
The link to the form itself is inside the python script.

A friend of mine asked me to write a bot which will autofill google form several times

To run it on MAC OS 10.14 you need to have python3 and install selenium
pip3 install -U selenium

Then modify the path to the chrome driver inside the python script to point to the current location of the project

Execute with
python3 google_forms_with_selenium
