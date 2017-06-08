# komoot-oauth2-connect-example
Example application to connect to komoot via oauth2

To use this demo code you need valid oauth2 credentials. You can apply for them here: https://www.komoot.de/b2b/connect#profileconnect .

## Run it locally

 1. (Fork and) clone the project.
 1. Create a python virtual environment ```virtualenv --distribute -p python3 .env```
 1. Activate the virtual environment ```. .env/bin/activate.fish``` (for the fish shell) or ```. .env/bin/activate``` (bash)
 1. Install dependencies ```pip install -r requirements.txt```
 1. Run the server application ```python test_client.py --client-id XXX --client-secret YYY```
 1. Open your browser [http://localhost:5000/](localhost:5000/) and login with a regular komoot user accout.
