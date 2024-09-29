--------------------Follow all the steps in cmd------------------------------------
1.create a virtual environment using python - virtualenv package(install it) - command after installing : python -m venv <envName>
2. Activate the environment created. cd to env folder: command: scripts\activate
3. now use pip to install all the packages in requirements.txt file
4. paste the wqp folder inside the environment
5. after installing earthengine-api, when the env is activated, run: #earthengine authenticate# and authenticate earthengine
6. cd to wqp folder-> now command: python manage.py runserver
7. Note: Do all the steps on when the environment is activate. Not when deactivated.