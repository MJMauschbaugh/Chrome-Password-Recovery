# Chrome-Password-Recovery
Password decrypter ran using pywin32 and PyCryptodome to decrypt saved google chrome passwords stored in 'Login Data' file.
This file is located in C:\~\AppData\Local\Google\Chrome\User Data\Default.
This program decrypts both older and newer encryption used by Chrome (before and after v80).

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.

```bash
pip install PyCryptodome
pip install pywin32
```
or 
```bash
python2 -m pip install PyCryptodome
python2 -m pip install pywin32
```
## Usage
  Program must be ran on Windows OS using python2, and on the source computer of the 'Login Data' sql file. 
```python
python2 Password Decrypter Chrome.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
