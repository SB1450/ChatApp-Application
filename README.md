This project contains ChatApp that works with MySql as its database, this app built for Docker

To execute ChatApp: cd to project root directory and run 'bash run.sh'. this will create 2 containers (app container, mysql container)

Steps:

1.  Run the "run.sh" script
```
bash run.sh
```

2. open your brower with this link: http://localhost:5000


And you will see the application. you can change rooms by adding room number after the port like this http://localhost:5000/room-number

Each room have it's own dialogs and the data saved in the MySql database


NOTE: When executing the ChatApp, most of the times it will take a few minutes to mysql container to initialize.


