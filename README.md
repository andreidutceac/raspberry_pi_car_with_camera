# raspberry_pi_car_with_camera
DIY project with a raspberry pi car and camera controlled from server

# Step 1: Set up Raspberry Pi

Install Raspbian OS on your Raspberry Pi and ensure it's connected to the Wi-Fi network.
Update the OS and install necessary packages:

# Step 1: Set up Raspberry Pi

Install Raspbian OS on your Raspberry Pi and ensure it's connected to the Wi-Fi network.
Update the OS and install necessary packages:
```ruby
sudo apt update
sudo apt upgrade
sudo apt install python3 python3-pip flask python-picamera
```

# Step 2: Hardware Assembly

Connect the motor driver board to your Raspberry Pi following the manufacturer's instructions.
Attach the motors to the motor driver board and connect the wheels to the motor shafts.
Attach the Raspberry Pi Camera to the Raspberry Pi's camera port.

# Step 3: Create a Flask Web Server

Create a directory for your project and set up the Flask application:
```ruby
mkdir car_project
cd car_project
```
Create a Python script for your Flask web server (e.g., app.py)
Create a templates directory and an HTML file (e.g., index.html) with control buttons to control the car.

# Step 4: Motor Control

Use the GPIO library to control the motors. You'll need to write functions in your Flask application that control the motors based on user input from the web interface.

# Step 5: Camera Control

Use the Picamera library to capture images or video. You can add routes to your Flask application to display the camera feed on your web interface.

# Step 6: Test and Run the Project

Run your Flask application on the Raspberry Pi:
![Capture](https://github.com/andreidutceac/raspberry_pi_car_with_camera/assets/117718437/e60479dd-ba1e-4ddc-94cf-049e062d4bd7)




