# Raspberry Pi Sensor Uploader using Sense HAT and Adafruit IO

This project reads temperature and humidity data using the Sense HAT on a Raspberry Pi and uploads it to Adafruit IO in real-time.

##  Features

- Reads temperature and humidity using Sense HAT
- Displays data on LED matrix
- Sends data to Adafruit IO feeds

##  Requirements

- Raspberry Pi with Sense HAT
- Python 3
- Adafruit IO account

##  Python Libraries Used

- `sense_hat`
- `adafruit-io`

Install them using:
```bash
pip install sense-hat adafruit-io

##  How to use
1) Reads sensor data from Sense HAT.

2) Sends the data to Adafruit IO feeds.

3) Displays the values on the Sense HAT LED matrix.

4) Repeats every 5 seconds.


