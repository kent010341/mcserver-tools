# mcserver-tools
Bash scripts for a Minecraft server run in a screen session.  

## tp
Expand the `tp` command in Minecraft.  
Using a simple cfg file to setup target label with its x, y, z.  

`Usage: ./tp [player] <location>`  

In order to add a new location, for example, to add a "basement" (-72, 45, 128), what you need is to simply add a newline:  

`locations["basement"]=-72,45,128`  

and then you can use `./tp <player> basement` to activate the `tp`!  
