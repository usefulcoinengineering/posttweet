Run the following commands to rapid setup:

```bash
git clone git@github.com:usefulcoinengineering/posttweet.git
cd posttweet
cp examples/example-credentials.py libraries/credentials.py
sudo apt install python3-pip
pip3 install requests_oauthlib
sudo timedatectl set-timezone America/Jamaica
```

Notes:

1. You need to edit credentials.py and add your Twitter API credentials.
2. You may need to execute the following command to install pip3 before installing the requests_oauthlib library:

```bash
sudo apt install python3-pip
```

Logfiles:

To make it easier to read the logfiles:

```bash
sudo timedatectl set-timezone America/Jamaica
```