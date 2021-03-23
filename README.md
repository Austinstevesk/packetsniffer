"# packetsniffer" 

#Using the sniffer
#Linux is the best to use for this
-Clone the repository
git clone https://github.com/Austinstevesk/packetsniffer.git

cd packetsniffer
-Install requirements
pip3 install requirements.txt

-Run the file 

root@austin:~/packetsniffer# python3 packetsniffer.py -i wlan0 --show-raw
    #Ensure your interface is the correct one use ifconfig to check
    -The output is sniffing your own computer

you can sniff packets all over the network or a specific host when you are a man-in-the-middle.

To do that, you need to arp spoof the target
