# pylinks

pylinks is a Python script that extracts links from a webpage URL

[![demo.jpg](https://raw.githubusercontent.com/domsalvador/pylinks/main/demo/demo.gif)](https://asciinema.org/a/nwKlx3NE4902559dS64NAXP3S)

- **Extracts all links** from a given webpage
- **Saves links to a text file** in the same directory as the script
- Uses regular expressions to **identify links** that uses **"http" or "https"**
- Can **handle any webpage** that can be accessed using a URL

## Requirements

- Python 3.x

If you have Python already installed, you can skip and continue to the next step.

```bash
sudo apt-get update && sudo apt-get install python3 -y
python3 --version
```

## Installation and Usage

```bash
git clone https://github.com/domsalvador/pylinks
cd pylinks
python3 pylinks.py 
```

## Sample Usage

```bash
$ python3 pylinks.py
Enter a URL: https://en.wikipedia.org/wiki/Ada_Lovelace

$ ls -CF
README.md  links.txt  notes/  pylinks.py

$ nano links.txt
```
