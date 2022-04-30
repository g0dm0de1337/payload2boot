# payload2boot
sh sh.sh

copy your "OTA.zip" in a new folder named "Boot" on your SD-Card.
(/sdcard/Boot/)

unzip the payload.bin in the folder 

go to termux
git clone https://github.com/g0dm0de1337/payload2boot

cd payload2boot
chmod +x *
sh sh.sh

wait for finished !!

cd $HOME/termux_payload

python payload_dumper.py payload.bin

cd $HOME/termux_dumper/output
