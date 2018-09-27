### September 26th 

When I tried to install keystone in the Fatima computer, the command "sudo yo keystone" gave an error.

The error message said can not access to a file in the directory (home)/.config/insight-node.

The problem has solved doing: "sudo chmod 777 (home)/.config/insight-node

### September 27th

After cloning the project the server gave an error when I tried to start it.

The node_modules project is missing because is not cloned from bitbucket.

To solve the problem I have to do: "npm install" in the project folder.
