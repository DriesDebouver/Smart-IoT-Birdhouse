# Smart IoT Birdhouse

## Smart Internet of Things Birdhouse based on a Raspberry Pi
Birdhouse with a camera that records video's when motion is detected inside.
Video's are saved on a USB stick and uploaded to a ownCloud storage server.
The Raspberry Pi has a battery and solar panel so it doesn't need power.
The Raspberry Pi is configured as a acces point so it doesn't need a internet connection.
When you come near the birdhouse with a device you can go on the ip address from the Raspberry Pi and acces the videos.

### Parts:
- Raspberry Pi 4 with Raspberry Pi OS (previously called Raspbian)
- Raspberry Pi NoIR Camera V2 (8MP)
- PIR motion sensor (HC-SR501)
- Optional: BMP280 & DHT11 temperature sensors

### Setup:
1. Download the included .zip file and extract it in the /home/pi folder on your Raspberry Pi
2. Run the "installation.sh" script and wait a very long time...
3. Go to http://192.168.50.1/owncloud and enjoy
