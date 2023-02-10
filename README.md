# fcommit

Program to format git messages according to [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)

## Installation

### Manual Installation

1. cURL
```
curl -s https://raw.githubusercontent.com/gabrielmusskopf/fcommit/main/install | bash
```

2. Make
````
git clone https://github.com/gabrielmusskopf/fcommit.git ~/fcommit
cd /fcommit

sudo make install

# uninstall
sudo make uninstal
````

## Usage
```
fcommit <option> <message>
```

Example
````
fcommit -ft "add a new file"
````

### Options

