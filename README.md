# FinTechM18Challenge
Module 18 Challenge Work

This challenge accomplishes the following main tasks:

* Create a new data class named Record. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.
* Change the existing Block data class by replacing the generic data attribute with a record attribute that’s of type Record.
* Create additional user input areas in the Streamlit application. These input areas should collect the relevant information for each financial record that you’ll store in the PyChain ledger.
* Test PyChain ledger.

![PyChain](PyChain.GIF)

## Technologies

This project leverages python 3.7.13 with the following packages:
```
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```

Before running the application first install the following dependencies.

```python
  pip install streamlit --upgrade
```

## Usage
To run the file, execute the command below at the command prompt
```
streamlit run pychain.py
```
## Contributors
---
[Sreedhar](j_sreedhar@yahoo.com)

## License
---
MIT
