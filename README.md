![Alt text](screenshot.jpg)

To Start Game:

-unzip directory into desired location

Linux
-cd directory
Start a server: 
	run "python server.py arg1 arg2"
	arg1 = port number ( number > 5000)
	arg2 = number of players 1-4
Start specified number of clients: 
	run "python client.py arg1 arg2"
	arg1 = port number same as server
	arg2 = host machines IP address

Windows
Run server
  Open command prompt
      C:> "cd directory\windows-exe\server"
    -Run server.exe takes two argument
      -arg1=port number, perferably choose number greater than 5000
      -arg2=number of clients(players), number between 1 and 4
      C:> server.exe arg1 arg2
      -Example: "C:> server.exe 5000 1" this starts a game on port 5000 with 1 player
Connect clients to server
  Open another command prompt
      C:> "cd directory\windows-exe\client"
    -Run client.exe takes two argument
      -arg1=IP address of computer running the server
	  -Note: use command "C:> ipconfig" on host machine to determine IP address
      -arg2=port number, choosen by server
      C:> client.exe arg1 arg2
      -Example: "C:> client.exe 127.0.0.1 5000"


-Note: Game only starts after all clients have connected which equal to the number of players


Game Play
	-Right click to select contry to move armies from
	-Left click to move armies into adjacent country
	-Number keys change quantity of armies moved
	*Note: The game quickly digresses into manical clicking*
