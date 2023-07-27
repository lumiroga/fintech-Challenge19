# Challenge XIX | Fintech <img src="https://instructure-uploads-pdx.s3.us-west-2.amazonaws.com/account_150420000000000001/attachments/590996/columbia.png" height="48" width="48">
---
This project is the eighteen challenge in the Columbia Fintech Bootcamp.

This challenge deals with Python Blockchain Programming, creating chains and ledger validation


---

## Streamlit application

A streamlit web app is the deliverable, this app allows the creation of a simple blockchain with Hash validation, multiple difficulty and a validation process, the app also allows the input of multiple Records in the blockchain.

<img src="pychain.png" >



### Form and inputs

Streamlit form for adding record elements into the blockchain
<img src="pychain_interface.png" >


### Block element details - Inspector

The application allows to inspect all the elements in the blockchain with the deatils, including the hash, sender, receiver and the nonce
<img src="pychain_blockinspector.png" >

Option to select and inspect an specific block
<img src="pychain_genesis_and_others.png" >

### Ledger  and Ledger Validation

Every time a new record is added to the blockchain, the record is added to the ledger list, validation can be done any time and when a record is added, this maintains the structure of the blockchain and makes it valid.

<img src="pychain_ledger.png" >

---

## Technologies

The main language is Python, with the following auxiliary modules/libraries.
Python version is 3.7, developed in an independent conda virtual environment

### pandas
This module handles DataFrames (dynamic tables), to maniupulate, store data, do automatic calculations and adding dynamic data.

Dataframes go hand in hand with streamlit, this permits easily printing tables and data (in this case the ledger data)

### dataclasses
This library allows the creation of dataclasses, for class member typing, this way class attributes can have a type and it automatically generates a class constructor with each attribute

### typing
Library for typing the class attributes (including list, int, float, and Any)

### datetime

Library for date and time manipulation, calculation and formatting

### streamlit

Library that creates a small web server and application that abstracts part of web development and permits the creation of simple but functional web apps including data formatting and form manipulation.

### hashlib

Libray for creating the hashes and validations of each of the blocks in the blockchain, helps maintaining the data integrity and securiy

---


### Clone repository
```bash
git clone https://github.com/lumiroga/fintech-challenge19.git
```
---

## Usage

Open the terminal

Go to solution folder in your local computer

```bash
cd ./fintech-challenge19
streamlit run fintech_finder.py
```


---

## Contributors

[lumiroga](https://github.com/lumiroga)

---

## License

* mpl-2.0 | Mozilla Public License 2.0