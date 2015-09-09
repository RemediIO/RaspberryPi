# Connect to Pi
ssh haoma@192.168.0.15

# Install VNC on Pi
sudo apt-get install tightvncserver

# Start VNC Server
vncserver :1 -geometry 800x600 -depth 24

# Connect to VNC Server From OSX
open vnc://haoma@192.168.0.15:5901