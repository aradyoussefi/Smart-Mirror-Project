# Smart Mirror Project

## Overview
I have designed and developed a Smart Mirror project to create an intelligent, interactive display that shows useful information while maintaining a sleek appearance. Currently, the project is implemented on a vertical monitor beside my coffee table, but I plan to convert it into a full-fledged smart mirror in the near future. This project utilizes Linux Mint and various software to achieve its functionality.

## Features
- **Real-time Clock and Date**: Displays the current time and date.
- **Weather Forecast**: Shows the current weather and a 7-day forecast.
- **News Feed**: Streams the latest news headlines.
- **Calendar Integration**: Syncs with my calendar to display upcoming events.
- **Compliments**: Displays random positive messages.
- **Voice Commands**: Responds to basic voice commands for hands-free interaction.

## Technologies Used
- **Operating System**: Linux Mint
- **Smart Mirror Software**: MagicMirror²
- **Programming Languages**: JavaScript, HTML, CSS
- **APIs**: OpenWeatherMap for weather data, News API for news headlines
- **Additional Tools**: npm, Electron, pm2
- **Remote Access**: NoMachine and NordVPN's Meshnet to connect to my server using any device, such as my laptop, to access and modify anything.

## Setup Instructions
1. **Install Linux Mint**: Ensure your system is running Linux Mint.
2. **Install Node.js and npm**: Required for running MagicMirror².
   ```bash
   sudo apt-get update
   sudo apt-get install -y nodejs npm
   ```
3. **Clone MagicMirror² Repository**:
   ```bash
   git clone https://github.com/MichMich/MagicMirror
   cd MagicMirror
   npm install
   ```
4. **Configure Modules**: Customize the `config/config.js` file to include desired modules and configurations.
5. **Start MagicMirror**:
   ```bash
   npm start
   ```
6. **Enable pm2 for Auto Start (optional)**:
   ```bash
   sudo npm install -g pm2
   pm2 start npm --name "magicmirror" -- start
   pm2 save
   ```

## Hardware In Use
- **Monitor**: Currently using a 24" monitor.
- **Dell Optiplex 5050**: As the main processing unit.

## Future Enhancements
- **Conversion to Mirror**: Integrate a one-way mirror glass and frame to complete the smart mirror functionality.
- **Facial Recognition**: To display personalized information based on the user.
- **Integration with Smart Home Devices**: To control smart home gadgets directly from the display.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

## Contact
For any questions or suggestions, feel free to contact me via [email](mailto:aradixix@gmail.com).
