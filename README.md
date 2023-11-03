# raspberry_pi_car_with_camera
DIY project with a raspberry pi car and camera controlled from server.
This project involves the creation of a Raspberry Pi-controlled car with integrated Pi Camera capabilities, all controllable through a web-based interface. By blending hardware components with software development, this project offers a practical, hands-on exploration of IoT, robotics, and web development concepts. It's a fun and educational endeavor that enables users to remotely control the car and capture real-time images or video from the onboard camera, all within an accessible web interface.

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

Access the web interface from a browser on another device by entering the Raspberry Pi's IP address and port.
# Step 7: Drive the Car

Use the web interface to control the car's movements and view the camera feed.
![Capture2](https://github.com/andreidutceac/raspberry_pi_car_with_camera/assets/117718437/5111bb28-ef6d-459d-a8e1-5b72b581c7d8)

