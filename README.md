# Embedded System Measurement Data Visualization Web Client

## Overview
This repository contains the source code for creating REST client applications to visualize measurement data from an embedded system on a web browser (e.g., Firefox, Chrome). The applications are designed to interact with an embedded device or a server mock to retrieve and display measurement data in the form of timeseries plots. Additionally, the client applications include modules for controlling user output devices (e.g., LED display) and configuring user settings.

## Features
- **Measurement Data Visualization**: Visualize timeseries plots of measurement quantities such as angular orientation (RPY), temperature, pressure, and humidity from the Sense Hat add-on. The interface provides clear and unambiguous interpretation of the data.
- **Dynamic Data Retrieval**: Cyclically request data from the server and display responses in the form of timeseries plots. Users can define the sample time according to their preferences.
- **User Output Device Control**: Control the state of user output devices, such as the LED matrix from the Sense Hat add-on. The interface clearly communicates the current user settings and whether they correspond to the output states.
- **Configuration and Settings**: Configure basic application settings including port number, server API version, request sample time, maximum number of saved samples, etc. User settings are saved on the server as a JSON text file for persistence across sessions.

## Getting Started
To run the client applications:
1. Clone this repository to your local machine using `git clone`.
2. Open the project in your preferred web development environment.
3. Modify the configuration settings in the appropriate files according to your setup.
4. Run and test the application on a selected web browser to ensure proper network communication.
5. Optionally, deploy the application to a physical or virtual embedded device for testing.

## Technologies Used
- HTML/CSS/JavaScript for frontend development.
- RESTful API for communication with the server.
- JSON for storing and retrieving user settings.

## Testing
The client applications have been tested on various web browsers to ensure compatibility and proper functioning. Additionally, network communication has been thoroughly tested to ensure seamless interaction with the embedded system or server mock.

## Contributors
- [Rohan Sanki](https://github.com/Edtheblack)

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Special thanks to [Dr. D.Luczak] for their valuable contributions and guidance.

---

Feel free to customize this README according to your specific project details and preferences.



if you look under i added the task pdf
