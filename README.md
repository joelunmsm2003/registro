sync && sudo sysctl -w vm.drop_caches=3
dpkg --get-selections
sudo apt-get --purge remove gimp

YOWSUP

apt-get install python-dateutil
apt-get install python-setuptools
apt-get install libevent-dev
apt-get install ncurses-dev
git clone git@github.com:tgalal/yowsup.git
git clone git@github.com:jlguardi/yowsup.git registro
cd yowsup
python setup.py install
yowsup-cli registration --requestcode sms --phone 51971254149 --cc 51 --mcc 716 --mnc 10
yowsup-cli registration --register 945-904 --phone 51971254149 --cc 51  

-- Response
status: ok
kind: free
pw: XOPt48WlBchys2mZo2THwVCogYQ=
price: US$0.99
price_expiration: 1485819467
currency: USD
cost: 0.99
expiration: 4444444444.0
login: 51988353108
type: existing

reinstall !!!
yowsup-cli demos --config whatsapp_config.txt --send 51964677408 "Hola causita"


Images
usr\src\imag1.jpg
yowsup-cli demos -d -c whatsapp_config.txt -i /home/andy/Escritorio/girl.jpg image
yowsup-cli demos --config whatsapp_config.txt --send 51988353108  '/home/andy/Escritorio/girl.jpg' image -d


 yowsup-cli demos -y -c whatsapp_config.txt
/message send 51935867751 'te paso una cancion de mi compu' 
/login 51971254149 V2zTjG0t7Q76jMbmgWepU8scAO4=
/image send 51964677408 '/home/andy/Escritorio/girl.jpg'
/profile setPicture '/home/andy/Escritorio/robot.jpg'
/video send 51964677408 '/home/andy/Escritorio/video.mp4'
/audio send 51964677408 '/home/andy/Escritorio/audio.mp3'
yowsup-cli demos -y -d then do /contacts

yowsup-cli demos -c whatsapp_config.txt -me 51964677408 '/home/andy/Escritorio/audio.mp3' audio
yowsup-cli demos -c whatsapp_config.txt -me 51964677408 '/home/andy/Escritorio/girl.jpg' image
yowsup-cli demos -c whatsapp_config.txt -me 51964677408 '/home/andy/Escritorio/video.mp4' 'video'


echo -e "/L\n/image send 51988353108 /home/andy/Escritorio/girl.jpg" | ./yowsup-cli demos -c whatsapp_config.txt -y &

kill %1

 Jose 51951571252
 Jacky 935867751
 Andres 51953570931


