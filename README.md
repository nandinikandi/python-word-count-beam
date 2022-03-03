# Nandini Kandi

# python-word-count-beam

### Instructions
* Open the folder 44-517,and create a new folder and name it as python-word-count-beam .
* Add the input.txt file and copy content from Shakespeare's sonnets
* create wordcount.py to count the words in Shakespeare's sonnets from the Apache Beam [examples](https://github.com/apache/beam/tree/master/sdks/python/apache_beam/examples).
* Complete Apache Beam Python SDK Quickstart using [https://beam.apache.org/get-started/quickstart-py/](https://beam.apache.org/get-started/quickstart-py/)
* Open powershell as administrator in your 44517\python-word-count-beam path
  * Check Python version 
```python --version```
  * Check pip version
```pip --version```

#### Get Apache Beam

* Create a virtual environment
  ```PS> python -m venv C:\path\to\directory ```
  
* Activate a virtual environment <br>
  ``` PS> C:\path\to\directory\Scripts\activate.ps1```

* Install the latest Python SDK from PyPI:
  ```PS> python -m pip install apache-beam```

* Execute a pipeline
  ```PS> python -m apache_beam.examples.wordcount --input input.txt --output output```





