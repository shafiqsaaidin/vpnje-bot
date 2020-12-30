# VPNJE-BOT
Basic mysql crud to manage my openvpn server

### Requirement
- openvpn server
- mysql server
- telegram bot
- nodejs

### Installation
1. git clone https://github.com/shafiqsaaidin/vpnje-bot.git
2. cd vpnje; npm install

### Configuration
1. make a new .env file which contain mysql server details
2. get telegram bot API key from bot father

### Make the bot run on startup
1. cd -f ./systemd/vpnje-bot.service /etc/systemd/system/
2. systemctl daemon-reload
3. systemctl enable vpnje-bot
4. systemctl start vpnje-bot 