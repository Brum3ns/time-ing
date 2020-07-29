#### Install time-ing:
```
git clone 
cd time-ing
pip3 -r requirement.txt
chmod +x time-ing
sudo cp time-ing /usr/bin
```

#### time-ing
```
use: ./time-ing url "postdata" usernames.txt timeout

example: ./time-ing https://www.domain.com/login "username=FUZZ&password=pa$$w0rd" usernames.txt 7 --> (FUZZ is the market for the username.txt to replace.)
```
