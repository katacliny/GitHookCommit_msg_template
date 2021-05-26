
# Commit MSG with python

This is a Python githook for dealing with branch strategy and common git mistakes.

## Installation

Copy the .githooks folder in your git repo and falow the intruction in the readme file inside that folder.


## Usage

Just try to make a invalid commit and you will see and output like this 

![image](https://user-images.githubusercontent.com/34369026/119501317-0ea76800-bd69-11eb-83e7-cc0055d6bd05.png)


## Contributing
Pull requests are welcome!

## License
[MIT](https://choosealicense.com/licenses/mit/)

#Install and use 

Run this command 'git config core.hooksPath .githooks' to add the hooks to your repo

##Dependencies

#command for Chocolatey  https://chocolatey.org/install

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

#for python3 

choco install python --version=3.8.0

#for ruby

choco install ruby

# for sass 

gem install scss_lint

# colorama

python -m pip install colorama
