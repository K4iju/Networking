# Lab Instructions: Connect and Configure Network Devices

## Scenario
You are creating a home office network. The network's internet access is connected to the left network port in the wall switch plate. You have selected a router and a wireless access point to use. Now you need to connect the devices and configure the network connections.

## 1. Connect the Router to the Internet

### Steps:
1. From the home office view, under **Computer Desk**, select **Hardware**.
2. Under **Shelf**, expand **Routers**.
3. Drag the router from the **Shelf** to the **Workspace** area.
4. Above the router, select **Back** to switch to the back view of the router.
5. Under **Shelf**, expand **Cables**.
6. Select the **Power Adapter**.
7. From the **Selected Component** pane:
    - Drag the **DC Power Connector** to the power plug on the router.
    - Drag the **AC Power Adapter** to the AC power plug on the surge protector.
8. Under **Shelf**, select **Cat5e Cable, RJ45**.
9. From the **Selected Component** pane:
    - Drag an **RJ45 Connector** to the WAN port on the router.
    - Drag the other **RJ45 Connector** to the left network plug on the wall plate.

## 2. Connect the Desktop Computers to the Router

### Steps:
1. Above the **PC1** computer case, select **Back**.
2. From the **Shelf**, select **Cat5e Cable, RJ45**.
3. From the **Selected Component** pane:
    - Drag an **RJ45 Connector** to a LAN port on the router.
    - Drag the other **RJ45 Connector** to the network plug on the computer.
4. Repeat Step 2 to connect **PC2** to the router.

## 3. Configure TCP/IP on the Desktop Computers

### Steps:
1. On the **PC1** monitor, select **Click to view Windows 11**.
2. Right-click **Start** and then select **Settings**.
3. Select **Network & internet**.
4. Select **Ethernet**.
5. From the right pane, scroll down to **IP assignment** and then select **Edit**.
6. Under **Edit IP settings**, use the drop-down list to select **Automatic (DHCP)**.
7. Select **Save**.
8. From the left pane of the **Settings** app, select **Network & internet** and verify that the computer has access to the internet.
9. From the top left, select **Computer Desk** to switch back to the **Workspace** view.
10. On the **PC2** monitor, select **Click to view Windows 11**.
11. Repeat steps 3b – 3h to configure **PC2**.

## 4. Connect the Wireless Access Point to the Router

### Steps:
1. From the top left, select **Computer Desk** to return to the **Workspace**.
2. Under **Shelf**, expand **Wireless Access Points**.
3. Drag the wireless access point from the **Shelf** to the **Workspace** area.
4. Above the wireless access point, select **Back** to switch to the back view of the wireless access point.
5. Under **Shelf**, expand **Cables**.
6. Select the **Power Adapter**.
7. From the **Selected Component** pane:
    - Drag the **DC Power Connector** to the power plug on the wireless access point.
    - Drag the **AC Power Adapter** to the AC power plug on the surge protector.
8. Under **Shelf**, select the **Cat5e Cable**.
9. From the **Selected Component** pane:
    - Drag an **RJ45 Connector** to the WAN port on the wireless access point.
    - Drag the other **RJ45 Connector** to a LAN port on the router.

## 5. Configure the Wireless Access Point

### Steps:
1. On the **PC1** monitor, select **Click to view Windows 11**.
2. From the taskbar, select **Google Chrome**.
3. In the URL field, enter `192.168.0.100` and press **Enter** to view the wireless access point management console.
4. In the **Windows Security** pop-up dialog, enter `admin` for the username.
5. Enter `password` in the Password field.
6. Select **OK**.
7. Maximize the window for better viewing.
8. From the left menu, select **Wireless**.
9. Select **Basic**.
10. Enter `HomeWireless` in the **Wireless Name(SSID)** field.
11. Select **Apply**.
12. In the **Windows Security** pop-up dialog, enter `admin` for the username.
13. Enter `password` in the Password field.
14. Select **OK**.
15. Under **Wireless**, select **Security**.
16. From the **Security Mode** drop-down list, select **WPA2-PSK** for authentication.
17. Under **WPA**, make sure **AES** is selected.
18. In the **Pass Phrase** field, enter `@hOMEwIRELESS!` as the security key.
19. Select **Apply**.

## 6. Configure the Laptop Wireless Connection

### Steps:
1. From the top left, select **Computer Desk** to switch back to the **Workspace** view.
2. On the front of the laptop, select the wireless switch to enable wireless networking.
3. On the laptop monitor, select **Click to view Windows 11**.
4. In the navigation area, select the network icon.
5. Select the arrow above **Available**.
6. Select **HomeWireless**.
7. Select **Connect Automatically**.
8. Select **Connect**.
9. Enter `@hOMEwIRELESS!` as the network security key.
10. Select **Next**.
11. Using your mouse, hover over the networking icon and verify that the laptop has a connection to the internet.

## 7. Configure the iPad Wireless Connection

### Steps:
1. From the top left, select **Computer Desk** to switch back to the **Workspace** view.
2. On the iPad screen, select **Click to view iOS**.
3. Select **Settings**.
4. Select **Wi-Fi**.
5. Under **NETWORKS**, select **HomeWireless**.
6. In the **Password** field, enter `@hOMEwIRELESS!` as the password.
7. Select **Join**.
