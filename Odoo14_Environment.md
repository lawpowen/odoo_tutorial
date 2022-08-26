# Odoo 14 environment



## 01.Python environment

### Check python in environment

```
python
python3
# need python 3.6-3.8
```

### install pip into environment

```ubuntu 
sudo apt-get install python3-pip
```

### Virtualenv (separate different project environment)

```
sudo apt-get install python3-virtualenv
virtualenv venv
source ./venv/bin/activate
```



## 02. Postgresql install

#### Address：https://postgresql.org/download/linux/ubuntu/

#### Install：

```
sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'
wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add - 
sudo apt-get update
sudo apt-get -y install postgresql-10
```

