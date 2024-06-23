<h1>Network Troubleshooting</h1>

<h2>Scenario</h2>
You are the IT administrator for a small corporate network. The person using the Office1 computer has called you and said that they can no longer access the network or internet. You suspect that the user has been adjusting their computer on their own.



## Steps to Verify the Problem

![alt text](image-10.png)

1. From the notification area, right-click the network icon and select **Network & Internet settings**.
2. Notice that you are shown that the computer has no connection to the internet.
3. Select **Advanced network settings**.
4. Under Related Settings, select **More network adapter options** to help determine why.
5. Notice the status for the network connection is **Network cable unplugged**.
6. Close the **Network Connections** window.
7. Close the **Settings** app.

## Steps to Resolve the Problem

![alt text](image-11.png)

1. Connect the cable.
2. From the top left, select **Office 1** to work with the computer hardware.
3. Above the computer, select **Back** to switch to the back view of the computer.
4. The computer has a network cable, but the link light is not on.
5. Select the network cable connected to the computer to see what is connected to the other end.
6. Notice that in the Selected Component pane, one end is unconnected.
7. Select the unconnected end and drag it to the network connection on the wall plate.

![alt text](image-13.png)

Note: When connected the RJ45 cable it detects the connection but is still not connected to the network

## Configure the IP Addresses

![alt text](image-16.png)
Note: This is the network topology for the building. We will use this to correlate the following information to the IP address settings.

![alt text](image-14.png)

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

![alt text](image-15.png)

1. Right-click **Start** and select **Windows Terminal**.
2. Type `ping 163.128.78.93` from the PowerShell prompt.
3. Press **Enter**.
