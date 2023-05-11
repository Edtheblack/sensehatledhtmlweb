Create REST client applications for a web browser (Firefox, Chrome, etc.) for embedded system
measurement data visualization.
(a) The interface should contain timeseries plots of at least two measurement quantities, e.g.
angular orientation (RPY) or temperature, pressure and humidity from the Sense Hat add-on.
Put on the chart all the necessary information for the correct and unambiguous interpretation
of the data. Use previously prepared graphic interface prototype designs.
(b) The application should cyclically request data from server and display responses in the form
of timeseries plot. The sample time should be dened by the user.
(c) Run and test app on a selected web browser. Make sure the network communication is
working properly. You can use a physical or virtual embedded device for testing, or a server
mock in the form of a local CGI script generating random synthetic measurement data.
2. Expand client application with module (web page) to control user output device (e.g. LED display).
(a) The interface should allow setting the state of all available user outputs (e.g. the LED matrix
from the Sense Hat add-on). The interface should clearly communicate whether the current
user settings correspond to the output states (i.e. whether the user has applied the last
changes). Use previously prepared graphic interface prototype designs.
(b) The application should send a request to the server containing control commands. Use an
adequate HTTP method.
(c) Run and test app on a selected web browser. Make sure the network communication is
working properly. You can use a physical or virtual embedded device for testing, or a server
mock in the form of a local CGI script saving control commands to text le.
3. Expand your application with a module (web page) to congure and save user settings.
(a) The conguration page should contain basic application settings, such as port number, server
API version (convenient for the developer), requests sample time, maximum number of saved
samples, etc.
(b) Conguration information should be saved on server as a JSON text le.
(c) After reloading web page, saved user's settings should be read from the server
