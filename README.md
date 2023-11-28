## Flask tour

### Create an environment
Create a project folder and a .venv folder within:

macOS/Linux
```
mkdir myproject
cd myproject
python3 -m venv .venv
```

### Activate the environment
Before you work on your project, activate the corresponding environment:

macOS/Linux

`. .venv/bin/activate`

Your shell prompt will change to show the name of the activated environment.

### Install Flask
Within the activated environment, use the following command to install Flask:

`pip install Flask`

### Run the server 
`index` is the name of main file

`flask --app index run` 