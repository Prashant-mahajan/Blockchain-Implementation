# Blockchain-Implementation
 
## Installation

1. Make sure [Python 3.6+](https://www.python.org/downloads/) is installed. 
2. Install [pipenv](https://github.com/kennethreitz/pipenv). 

```
$ pip install pipenv 
```

3. Create a _virtual environment_ and specify the Python version to use. 

```
$ pipenv --python=python3.6
```

4. Install requirements.  

```
$ pipenv install 
``` 

5. Run the server:
    * `$ pipenv run python blockchain.py` 
    * `$ pipenv run python blockchain.py -p 5001`
    * `$ pipenv run python blockchain.py --port 5002`

Use [Postman](https://www.getpostman.com) to interact with the API 

## Functionalities: 

1. `/transaction/new, /mine, /chain, /noedes/register`
2. Implemented Basic Proof of Work 
3. Implemented Consensus Algorithm 

## Reference: 
Use [this](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46) amazing article for the reference. 