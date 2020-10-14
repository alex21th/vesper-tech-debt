### Virtual environment setup

**1. Create a virtual environment on your local repository**

Check you have Python 3 version:

```py
$ python3 --version
Python 3.6.2
```

Create venv:

```
$ python3 -m venv vesper_env
```



**2. Activate it to install packages and to execute scripts (ALWAYS!)**

```
$ source ./vesper_env/bin/activate
(vesper_env) @Username/:
```

You can deactivate it with:

```
$ deactivate
```



**3. Install `requirements.txt`**

With the environment activated:

```
$ pip install -r requirements.txt 
```



**4. Add new packages to the project, if needed**

```
$ pip install new_package_name
$ pip freeze -l > requirements.txt 
```

