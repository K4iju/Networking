<h1>Network Troubleshooting</h1>

<h2>Scenario</h2>
You are the IT administrator for a small corporate network. The person using the Office1 computer has called you and said that they can no longer access the network or internet. You suspect that the user has been adjusting their computer on their own.



## Steps to Verify the Problem

![image](https://github.com/K4iju/Networking/assets/159083256/b8b2cff6-c7da-4aa8-8a1f-46ec88e9b8c4)


1. From the notification area, right-click the network icon and select **Network & Internet settings**.
2. Notice that you are shown that the computer has no connection to the internet.
3. Select **Advanced network settings**.
4. Under Related Settings, select **More network adapter options** to help determine why.
5. Notice the status for the network connection is **Network cable unplugged**.
6. Close the **Network Connections** window.
7. Close the **Settings** app.

## Steps to Resolve the Problem

![image](https://github.com/K4iju/Networking/assets/159083256/e6387946-9cac-49a8-a0bb-55b467f6116e)


1. Connect the cable.
2. From the top left, select **Office 1** to work with the computer hardware.
3. Above the computer, select **Back** to switch to the back view of the computer.
4. The computer has a network cable, but the link light is not on.
5. Select the network cable connected to the computer to see what is connected to the other end.
6. Notice that in the Selected Component pane, one end is unconnected.
7. Select the unconnected end and drag it to the network connection on the wall plate.

![image](https://github.com/K4iju/Networking/assets/159083256/70924f61-3bb5-4cb5-ab30-95de96bfc1c4)


Note: When connected the RJ45 cable it detects the connection but is still not connected to the network

## Configure the IP Addresses
![image](https://github.com/K4iju/Networking/assets/159083256/ea42414a-8eb8-44b9-88b1-9788f6212bf9)

Note: This is the network topology for the building. We will use this to correlate the following information to the IP address settings.

![image](https://github.com/K4iju/Networking/assets/159083256/82af174e-ce0d-43be-9dbb-d0ed21a124a5)


1. On the monitor, select **Click to view Windows 11** to switch to the operating system view.
2. The notification area shows a network connection.
3. Right-click **Start** and select **Settings**.
4. Select **Network & internet**.
5. Select **Ethernet**.
6. For **IP assignment**, select **Edit**.
7. Use the **Edit IP setting** drop-down list to select **Manual**.
8. For **IPv4**, make sure the button is slid to the **ON** position.
9. Configure the fields as follows:
    - **IP address**: valid IP address (such as `192.168.0.27`)
    
    Note: The IP address can range from 192.168.0.16 - 192.168.0.29 because below .15 are being used by servers and .30 - .34 are being used by other workstations
    - **Subnet mask**: `255.255.255.0`
    - **Gateway**: `192.168.0.5`
    - **Preferred DNS**: `163.128.78.93` or `163.128.80.93`
10. Select **Save**.
11. Close the **Settings** app.

## Verify a Connection to the Internet

![image](https://github.com/K4iju/Networking/assets/159083256/c841022c-c9a2-4c9c-ab47-4fcd0604a118)


1. Right-click **Start** and select **Windows Terminal**.
2. Type `ping 163.128.78.93` from the PowerShell prompt.
3. Press **Enter**.
