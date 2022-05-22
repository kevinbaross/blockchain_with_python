# Blockchain with Python

In this project, a blockchain-based ledger system is built with a user-friendly web interface. 
This ledger enables partner banks to undertake financial transactions (i.e., money transfers between senders and receivers) as well as validate the ledger's data integrity.


---

## Technologies

This project leverages VS Code and Streamlit.

---

## Installation Guide

Before running the application, please install the following libraries and dependencies

```python

pip install streamlit

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib

```

Then, clone the repository onto your local computer.

---

## Program Usage

For Mac user, open terminal then navigate to your folder.

First, don't forget to activate your dev environment with the following command.

```python
conda activate dev
```

Then open the program with the following command.

```python
streamlit run pychain.py
```

The following screen will load up.

Screenshot
  
Next, you can keep adding transaction information by adding sender, receiver, and amount information, and click "Add Block"
The ledger on the bottom of the screen will be updated each time you enter the new block.

Screenshot
   
You can also choose the difficulty level on the left side of the screen, and validate the chain (at the bottom of the screen) to ensure data integrity.



---

## Contributors

Initial code is provided by: UC Berkeley Fintech Bootcamp

Code is modified by: Kevin BaRoss [[LinkedIn](https://www.linkedin.com/in/kevin-baross/)]


---
