# Pi-Hole-Installation-Configuration-Tutorial
[![Pi-Hole-Installation-Configuration](https://img.youtube.com/vi/n8cLpYRuNFA/maxresdefault.jpg)](https://www.youtube.com/watch?v=n8cLpYRuNFA)

# Getting Started


 ### To install Pi-hole on an Ubuntu Server machine, you need to ensure that you meet the following prerequisites: 
- A machine running Ubuntu Server v22.04.2.
  - System requirements: Pi-hole has minimal system requirements, but it's recommended to have at least a Raspberry Pi or equivalent hardware with a 1GHz processor and 1GB RAM. Ensure that your Ubuntu Server machine meets or exceeds these requirements.
- Up-to-date system: It's always recommended to have an updated Ubuntu Server system. Run the following commands to update your system before installing Pi-hole:
```sh
sudo apt update
sudo apt upgrade
# system update/upgrade commands
  ```
- Windows client on the same network as your Pi-Hole machine
# Intalling Pi-Hole

Run the following command in your Ubuntu terminal
```sh
sudo curl -sSL https://install.pi-hole.net | bash
# intalls Pi-hole to Ubuntu machine
```
Pi-Hole GUI configuration shown in tutorial > [(See Here)](https://www.youtube.com/watch?v=n8cLpYRuNFA?t=105)

# Change Pi-Hole default password

```sh
pihole -a -p (your password)
# changes default password
```
# Windows Pi-Hole web interface
#### Step 1: Open browser > type IP address of your Pi-Hole server "10.0.0.158" followed by "/admin"
- This take you to the Pi-Hole admin page
#### Step 2: Login to Pi-Hole via admin page
# Windows DNS configuration
![ph1](https://github.com/S-Hill256/Pi-Hole-Installation-Configuration/assets/138057919/dcf9206a-dc55-47e8-873e-3b19baf11903)

#### Step 1: Open "Network & Internet Settings"

![ph2](https://github.com/S-Hill256/Pi-Hole-Installation-Configuration/assets/138057919/b0d2a375-e952-47cc-93a7-3cfd2c8febd7)

#### Step 2:  Open "Change adapter options"

![ph3](https://github.com/S-Hill256/Pi-Hole-Installation-Configuration/assets/138057919/c4a1a868-aa0c-4fe2-a898-88fbe453a698)

#### Step 3:  Right click and select properties

![ph4](https://github.com/S-Hill256/Pi-Hole-Installation-Configuration/assets/138057919/3d2b13f5-9c72-45be-aa2c-fcd82a860a27)

#### Step 4:  
- Select "Use the following DNS server addresses"
  - In "Preferred DNS server:" Put your Pi-Hole IP Address
    - Click "OK" to confirm
