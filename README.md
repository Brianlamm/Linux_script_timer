# Linux_script_timer
Weather script
1. Create a bin directory by runiing: mkdir bin
2. Put the weather_script in the bin directory
Weather service and timer 
1. save both weather_script.service and weather_script.timer in your home directory, you can go to yout home direcotry by running: cd ~
2. make sure systemd is init
After that follow theses command:
1. sudo cp weather_script.service /etc/systemd/system
2. sudo cp weather_script.timer /etc/systemd/system
3. sudo systemctl daemon-reload
4. sudo systemctl enable --now weather.timer
