RTRisk: Real Time Risk

Starting Game:
Note: "C:>" signifies running command in command prompt

1. Copy or move RTRisk folder to desktop
2. Run server
  a. Open command prompt
    -Change present working directory to "desktop\RTRisk\server" 
      C:> cd Desktop\RTRisk\server
    -Run server.exe takes two argument
      -arg1=port number, perferably choose number greater than 1000
      -arg2=number of clients(players), number between 1 and 4
      C:> server.exe arg1 arg2
      -Example: "C:> server.exe 5000 1" this starts a game on port 5000 with 1 player
    -Note: server will not start game until the selected number of clients(players) have connected
3. Connect clients to server
  a. Open another command prompt
    -Change present working directory to "desktop\RTRisk\client" 
      C:> cd Desktop\RTRisk\client
    -Run client.exe takes two argument
      -arg1=IP address of computer running the server
	  -Note: use command "C:> ipconfig" on host machine to determine IP address
      -arg2=port number, choosen by server
      C:> client.exe arg1 arg2
      -Example: C:> client.exe 192.168.61.199 5000
    -Note: Repeat step 3 for each player in the game, the number specified by the server

Note: these directs assume that "RTRisk" is on the Desktop, obviously one could move the directory and modify the directions accordingly

       