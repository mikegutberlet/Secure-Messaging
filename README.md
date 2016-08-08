Secure-Messaging App

## Requirements and Setup
First of all you need Redis:
```Bash
sudo apt-get install redis-server
```
Next you need the following python packages:
```Bash
sudo pip install tornado
sudo pip install git+https://github.com/evilkost/brukva.git
```
Finally clone this repository:
```Bash
git clone https://github.com/mikegutberlet/Secure-Messaging.git chat
cd chat
```

## Run Application
You can run the application on a specific port like that:
```Bash
python app.py --port=8888
```
Open `localhost:8888` in your browser and see the result!
