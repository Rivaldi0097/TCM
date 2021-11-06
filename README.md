# PhrisFoo TCM

## Build Setup (Preferably run on windows)

1. Unpack the zip file and place the folder under your WAMP/MAMP root directory
2. Run WAMP (on Windows) or MAMP (on MacOS) Server
3. Go to phpmyadmin, login, and select the “SQL” tab
4. Copy the contents of Database_init.sql and paste them into the “SQL” tab (see note no. 3)
5. Run Docker
6. Open CMD and move to the TCM directory
7. Run “docker-compose up -d” on CMD (this will take awhile)


## If running on MAMP, please do following steps:
Go to the MAMP phpmyadmin. Under the SQL tab, please run the following code. 
“SET GLOBAL event_scheduler = ON;” -- Please run this everytime MAMP server is restarted (unless the default has been set to set event_scheduler to be on)

There is a known bug whereby the “Book Now” button sometimes doesn’t work on Mac. If this happens, simply refresh the page and it should work just fine.


