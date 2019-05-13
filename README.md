## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

### Installation
Run the script and follow the assistant:

`wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

### I want to run my own VPN but don't have a server for that
You can get a VPS from just $1/month at [VirMach](https://billing.virmach.com/aff.php?aff=4109&url=billing.virmach.com/cart.php?gid=1).

### Donations

If you want to show your appreciation, you can donate via [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VBAYDL34Z7J6L) or [cryptocurrency](https://pastebin.com/raw/M2JJpQpC). Thanks!










### HALLO Hello

multi-openvpn-install.sh 
### EN
Server 1 - Server xx
You can have a large number of your own servers
Following settings
server 1 has VPN tunnel with internet
server 2 has server to server vpn
server 3 has server to server vpn
server 4 has server to server vpn
......



Start the script
bash multi-openvpn-install.sh 1
for more servers
bash multi-openvpn-install.sh 2
for more servers
bash multi-openvpn-install.sh 3

By default, Server 1 has Internet and Forced Redirection in VPN.
On server 2 is by default NO internet and NO forcing diversion in VPN


that can be changed
this is in position
218-224
Clone this section
to a new position underneath
225 +
Then change
if [$ servermodel -eq "1"]; then
to
if [$ servermodel -eq "2"]; then
And they have 2 Internet VPN tunnels

Server 3 is then again by default NO internet and NO forcing diversion in VPN
So server to server ;)














### DE
Server 1 - Server xx
Sie können eine große anzahl an eigenen server haben
Folgende einstellungen
server 1 hat VPN tunnel mit internet
server 2 hat Server zu Server vpn
server 3 hat Server zu Server vpn
server 4 hat Server zu Server vpn
.....

Starten sie das skript
bash multi-openvpn-install.sh 1
für mehr server
bash multi-openvpn-install.sh 2
für mehr server 
bash multi-openvpn-install.sh 3


Server 1 hat standardmäßig internet und zwangsumleitung in VPN.
Auf server 2 ist standardmäßig KEIN internet und KEINE zwangsumleitung in VPN

das kann geändert werden
dies ist an Position
218-224
Klonen sie diesen abschnitt
auf eine neue position darunter
225 +
Ändern Sie dann
if [ $servermodell -eq "1" ]; then
zu
if [ $servermodell -eq "2" ]; then
Und die haben 2 Internet VPN tunnel

Server 3 ist dann aber wieder standardmäßig KEIN internet und KEINE zwangsumleitung in VPN
also server zu server ;)

