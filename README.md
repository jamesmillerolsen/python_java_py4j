# python_java_py4j

This project is to practice the use of Python with Java using Py4j.

Links
    Py4j Getting Stated
        https://www.py4j.org/getting_started.html
    Maven py4j:  
        https://mvnrepository.com/artifact/net.sf.py4j/py4j/0.10.9.5
    

Could not get Intellij to work with WSL Java and Python, so resorted to using Windows install of both
Also could not get Intellij to find/recognize a Python Virtual Env created outside of Intellij, 
    so I created a virtual environment from Intellij and them opened a Terminal to "activate" it and install
    additional packages to it.
```
File -> Settings -> SDKs -> + -> Add Python SDK -> Virtualenv Environment -> New environment ->
    Location = <your repo module + venv> -> OK
File -> Settings -> Modules -> <your module> -> <select the virtualenv you just created, in the dropdown> -> OK

To Activate and install new packages, from the Terminal:
source venv/Scripts/activate

python -m venv --copies thick_venv


```


