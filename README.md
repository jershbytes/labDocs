# Setup

If you want to contribute to this site the best way ist to install mkdocs-material.

It's quick and easy and just requires some steps.

### Install Python
- Windows
```pwsh
winget install Python.Python.3.13
```
- MacOS
```zsh
brew install python@3.13
```
- Ubuntu
```bash
sudo apt install python3
```
Also make sure **pip** is installed
### Clone the repo. *(If You have access)*

```
git clone https://github.com/jershbytes/wow-raiding.git
```

### Setup venv

```bash
# -- Change into Dir
cd wow-raiding

# -- Setup the venv
python3 -m venv venv

# -- source the venv
source venv/bin/activate

# -- Install mkdocs-material and mkdocs-material[imaging]
pip install mkdocs-material
pip install "mkdocs-material[imaging]"

# -- launch the server
mkdocs serve
```

From there you should be able to make edits.

> [!NOTE]
> Since this is hosted on Cloudflare pages any time a push is made this will rebuild and load the changes. So make sure you dev locally then push.
