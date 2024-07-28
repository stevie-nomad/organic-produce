# Organic Produce

A ecommerce web application for organic produce.

##  Getting started
1)  Clone the repository
    ```bash
    git clone git@github.com:stevie-nomad/organic-produce.git 
    ```

2)  Create a virtual environment
    First we need to change to the django app source directory.
    ```bash
    # Change the directory git repository `src/` folder
    cd organic-produce/src
    ```
    Then we need to activate a virtual environment with the python dependecies.
    If we don't already have one, we're using Python 3.12 (anything above 3.10 is OK)
    ```bash
    # in the root directory of the project
    python -m venv venv
    ```
    Activate the virtual envrionment
    ```bash
    source venv/bin/activate
    ```

3)  Install dependencies
    For this we need to switch the the `src` folder
    ```bash
    cd src/
    ```
    Now install the projects python depdencies
    ```bash
    pip install --upgrade pip && pip instal -r requirements.txt
    ```

4)  Start the django application
    ```bash
    python manage.py runserver
    ```
