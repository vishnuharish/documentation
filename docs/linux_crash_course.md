#Linux Crash Course - Learn Linux TV

## Usermod 

- The usermod command used to modify the user .

` sudo usermod -aG admins harish`

- The above example states that to add the user into the **admins** Group. This command also supports adding user to multiple groups.

`sudo usermode -aG admins, sudo harish` 

- With the ` usermod ` command we can change the users ` home ` directory.

` sudo usermod -d /home/myhome harish `

- We can also copy the existing files on the home directory to using `-m` or `--move-home` option.

` sudo usermod -d /home/myhome -m harish `

- Using ` usermod ` command we can lock an user's account.

` sudo usermod -L harish `

- To unlock an user we can use `-U` command .

` sudo usermod -U harish `

- Using the `usermod` command we can change the username of an user.

` sudo usermod -l hg harish`

- We can set the expiration time to an user's account using `usermod` command
` sudo usermod harish -e 04/17/2023 `

## Groups

- Creating a new group in the linux terminal.

` sudo groupadd admins`

- User can check their groups by using `groups`
 
` groups `

## Sudo

Sudo command is the abbrevation of Super User DO. This command helps the users to elevate privileges to perform an action or task using command line or bash.



