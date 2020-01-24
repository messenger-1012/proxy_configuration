


## Requirements
    <h4>Python3</h4>
    To install python3 go to http://python.org

## About
    This is a script which configures removes the hassle of configuring proxy manually by supporting system wide proxy_configuration.
    It is kept as simple as possible . No extra library other than the one that comes with python3 is used.

    Currently tested on Ubuntu 14.04, 16.04, 18.04.

    There are four options
    1)Set proxy : Takes input from the user and modifies the required files.
    2)Remove proxy : Remove any proxy settings if present in the files.
    3)View Proxy : Displays the current proxy settings if there are any.
    4)Restore default : Restores to the state before running this script for the first time.

## Run 

```
chmod +x proxy.py
sudo ./proxy.py
```

## Support
    Currently it modifies the following files
    1)/etc/apt/apt.conf
    2)/etc/environment
    3)/etc/bash.bashrc


## contribution
    contributors are more than welcome to contribute to this project.
   
