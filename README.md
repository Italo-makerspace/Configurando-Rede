Configuring the Network on the Archer AX6000
============================================

Properly configuring the Archer AX6000 router is essential for ensuring a fast, secure, and efficient internet connection. The following steps provide a comprehensive guide that anyone can follow to complete this setup safely, even without prior technical experience.

Step 1 -- Accessing the Configuration Panel
------------------------------------------

First, connect your computer or mobile device to the router via an Ethernet cable or Wi-Fi. Next, open a web browser and enter the Archer AX6000's default IP address: `192.168.0.1`.

Upon your first access, the router will prompt you to create a new administrator password. Choose a strong password, such as `Italo2025!@`, to prevent unauthorized access to the control panel.

After setting the password, the system will ask for your internet connection type. Most Brazilian providers use **Dynamic IP**, so this option should be selected.

Step 2 -- Wireless Network Configuration
---------------------------------------

Once in the control panel, navigate to `Wireless > Wireless Settings`. Disable the **Smart Connect** feature, which combines the 2.4GHz and 5GHz networks into a single one, to configure each band separately.

In the **SSID** (network name) field, define simple and easily identifiable names:

-   For 2.4GHz: `Italo_Home_2G`

-   For 5GHz: `Italo_Home_5G`

In the **Password** field, set a secure password for both networks, for example: `StrongPassword2025#`.

For the **Security** option, select `WPA2-PSK` with `AES` encryption, which is currently the most secure combination available.

Step 3 -- Advanced Wireless Adjustments
--------------------------------------

Proceed to `Advanced > Wireless > Wireless Advanced` to optimize the signal:

-   **Mode**:

    -   2.4GHz: `802.11ax/n/b/g mixed`

    -   5GHz: `802.11ax/ac/n mixed`

-   **Channel**:

    -   2.4GHz: Manually select channel **3** to avoid interference from neighboring networks.

    -   5GHz: Leave on **Auto (with DFS enabled)**, allowing the router to automatically select the best channels.

-   **Channel Width**:

    -   2.4GHz: Adjust to **40 MHz**

    -   5GHz: Adjust to **80 MHz**

-   **Transmit Power**: Set to **High** to ensure maximum network range.

> **For example:** Channels 1, 6, and 11 are commonly used, so selecting channel 3 can reduce interference in apartment buildings. An 80 MHz channel width on the 5GHz band is ideal for streaming and online gaming, as it allows for greater simultaneous data transfer.

Step 4 -- Securing Against Unauthorized Access
---------------------------------------------

Navigate to `Advanced > System Tools > Administration` to secure the control panel. Here, verify that the administrator password is up to date and difficult to guess.

Next, go to `Advanced > Wireless > WPS` and **disable WPS**. While this feature simplifies connections, it also poses a security risk.

Then, access `Security > Remote Management` and ensure the **Disable** option is checked. This blocks unauthorized remote configuration attempts.

Step 5 -- Firmware Update and Backup
-----------------------------------

In the `System Tools > Firmware Upgrade` menu, click **Check for Upgrade Online**. If a newer firmware version is available, perform the update. This ensures enhanced security and stability.

In `System Tools > Backup & Restore`, click **Backup** and save the configuration file. This file can be used to restore your settings if the router is ever reset in the future.

Step 6 -- Quality of Service (QoS) and Prioritization
----------------------------------------------------

Finally, navigate to `Advanced > QoS (Quality of Service)`. Enable the **By Device** mode and select which devices should have priority---such as a laptop used for work or a gaming console. This ensures these devices maintain the best connection, even when other users are streaming videos.

Also, enable the **Airtime Fairness** feature, which prevents slower devices from degrading the performance of others on the network.

> By following these steps, your network will be configured for security, efficiency, and stability. The channels and channel widths have been adjusted to minimize interference, and protection against unauthorized access has been reinforced.
