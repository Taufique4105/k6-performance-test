# k6-performance-test
**Installation**

I have used following command to set-up K6 on my Linux system

sudo apt update && sudo apt install -y gpg
curl -fsSL https://dl.k6.io/key.gpg | sudo gpg --dearmor -o /usr/share/keyrings/k6-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/k6-archive-keyring.gpg] https://dl.k6.io/deb stable main" | sudo tee /etc/apt/sources.list.d/k6.list
sudo apt update && sudo apt install -y k6

To check version use : 
k6 version

**First Script using bash**

I have created a directory for my tests : 
mkdir -p ~/k6-tests && cd ~/k6-tests

Then I created a simple test script file : 
nano test.js

Then wrote the script and to save in nano : 
press CTRL + X, then Y, then ENTER.


