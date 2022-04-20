# electrsinstall
Automatic install script for romanz electrs.  Built for the FutureBit Apollo.

I manually installed Tor and electrs on my Futurebit.  I took the commands and put them into an installer.

I think this will only work on the FutureBit Apollo as parts are hardcoded to the Futurebit's NVME drive.

Installs prerequisites, Tor, romanz electrs, prometheus, electrs.service, and some defaults.  The electrs database is set with 777 permissions.  I need to find what permissions it actually requires still.

The installer will probably take 30+ minutes to run and 6 hours to actually sync.

https://github.com/romanz/electrs

To run:

git clone https://github.com/apurgert/electrsinstall
cd electrsinstall
chmod 777 installelectrs.sh

./installelectrs.sh
