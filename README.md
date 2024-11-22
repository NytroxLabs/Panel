Supported And Unsupported Versions!

__________________________________________________
Ubuntu 24.04 ✅

__________________________________________________
Ubuntu 22.04 ✅	

__________________________________________________
CentOS 7     ✅

__________________________________________________
CentOS 8	    ✅

__________________________________________________
Debian 11	 ✅	

__________________________________________________ Debian 12	 ✅	

__________________________________________________
Windows 11	 ⚠️

__________________________________________________

Windows 10	 ⚠️	

__________________________________________________

macOS 10.15+ ⚠️	

__________________________________________________


# NytroxPanel

Welcome to **NytroxPanel**, the ultimate tool for managing and controlling your gaming servers! Whether you're running a small private server or a large gaming community, ~~NytroxPamel~~ provides a user-friendly interface and powerful features to enhance your gaming experience.

# Features

- **Multi-Game Support**: Manage servers for various games in one place.
- **User Management**: Easily add, remove, and manage user permissions.
- **Real-Time Monitoring**: Keep track of server performance and player activity.
- **Automated Backups**: Schedule regular backups to protect your game data.
- **Custom Configurations**: Modify server settings with ease using the intuitive interface.
- **Mod and Plugin Management**: Easily install and update mods and plugins.

# Installation

1. Choose Destination:
   ```bash
   cd /etc
   ```
2. Clone the repository:
   ```bash
   git clone v0.1.1 https://github.com/NytroxLabs/Panel.git
   ```
2. Navigate to the directory:
   ```bash
   mv panel nytrox
   cd nytrox
   npm install
   ```
3. Seed & Create a User:
   ```bash
   npm run seed
   npm run createUser
   ```
4. Setup Complete:
   Now you need to do now is start Nytrox:
   ```bash
   node .
   ```
__________________________________________________
# For Production Applications
- **To deploy `nytroxpanel` efficiently in production, using PM2 or alternatives is recommended. Below are the standard PM2 setup steps.**

**Run the following command to install PM2:**
```
npm install pm2@latest -g
pm2 start index.js
```

# Advanced Users: Auto-Run on Startup
**With the PM2 process running in the background, run the following command:**
```
pm2 startup
```
**Then, to 'freeze' the running processes, run the following command:**
```
pm2 save
```

# Usage

After installation, access GamePanel via your web browser:

```
http://localhost:3001
(unless you changed it in `config.json`)
```

Log in with your admin credentials and start managing your servers!


# License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

# Contact

For support or inquiries, please reach out to [help@nytroxlabs.com](mailto:zenpaizombiewww@gmail.com)

---

**NytroxPanel** An Ultimate Recreation Of ~~Pterodactyl Panel~~!!
