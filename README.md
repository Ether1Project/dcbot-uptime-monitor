#Guide to add servers to uptime bot:

in the file "server-monitor" you will see the current config for the bot.
You can open a PR with requested changes (add more sites to track like cloud team etc), this you can do by doing the following;

Copy the last added website. example=

		}, {
		    "Name": "Xerom Wallet Website",
            "Address": "wallet.xerom.org",
            "Port": 80	
		}	
    
paste it under the } icon from copied last one.

make sure to it starts with 
}, { and end with }

"Name" edit this to your likings
"Address" the website address
"port" should remain 80

submit PR and i apply changes ASAP
