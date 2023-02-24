# WakeOnLAN-Bot

This is a simple Discord bot that can be used to wake up a computer using Wake-On-LAN (WOL). It also includes some additional commands such as ping and uptime, and the ability to evaluate and execute arbitrary code.
Big thanks to [m4](https://github.com/m4tonoob/) for helping me with the JS part.

## Installation

1. Clone the repository: `git clone https://github.com/tarun5060/WakeOnLAN-Bot`
2. Install dependencies: `npm install`
3. Update the `config.json` file with the following fields:
	 - `ownerID`: The Discord user ID of the bot owner
   - `token`: Your Discord bot token
   - `ipAddress`: The IP address of the computer you want to wake up
   - `macAddress`: The MAC address of the network interface on the computer you want to wake up
5. Run the bot: `node index.js`

## Usage

Once the bot is running, you can use the following commands:

- `wake`: Sends a WOL magic packet to wake up the computer*
- `ping`: Displays the bot's latency and the API latency
- `uptime`: Displays the bot's uptime in hours
- `eval`: Evaluates JavaScript code*
- `exec`: Executes a shell command*
- `status`: Pings the computer and displays the result*

`*owner only`

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.


## Contact & Support
If you encounter a bug or an issue, feel free to reach me 
- Discord: [`Tarun#0001`](https://discord.com/users/603592344348000266)
- Twitter: [`@_tarun0`](https://twitter.com/_tarun0)

If you wish to support me and this project, you can do so [here](https://buymeacoffee.com/trnx0). Appreciate it :)