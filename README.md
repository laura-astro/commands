# Linux Terminal

### Basic command lines

* To open and unzip a file:
```bash
tar -zxvf example.tgz
```

* To make .png or .txt files into a list:
```bash
ls TIC*.png > list
```

* To remove ".png" from files:
```bash
sed -i 's/\.png$//' file.png
```

* To add ".txt"  to files:
```bash
sed -i 's/$/.txt/' file.txt
```

* To backup an original file:
```bash
sed -i.bak 's/\.png$//' file
```

### Command lines to create a virtual environment and install packages

* To create the environment:
```bash
python -m venv envname
```

* To activate the environment:
```bash
source envname/bin/activate
```

* To install requirements:
```bash
pip install -r requirements.txt
```

* To check the list of installed packages:
```bash
pip list
```
