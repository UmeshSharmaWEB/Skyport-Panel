#                            Installation The Panel

!Run As Root Following This Command = Sudo Su

Install The Panel=
bash <(curl -s https://raw.githubusercontent.com/UmeshSharmaWEB/Skyport-Panel/refs/heads/main/panel)

#                          Installation The Node

!Run As Root Following This Command = Sudo Su

Install The Node=
bash <(curl -s https://raw.githubusercontent.com/UmeshSharmaWEB/Skyport-Panel/refs/heads/main/wings)

Open Directory=
cd skyportd

Paste Your Node Configure

Start The Node=
pm2 start . 

#                     After Panel Stop Restart Your Panel

Start The Panel=
pm2 start index

Start The Node=
pm2 start skyportd    
