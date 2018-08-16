# sql-connection
# Read me 
This connection aims to auto populate data from mysql local environment to google sheet. Everytime when executes the python scripts in Scripts.ipynb, it will populate all the stats from the latest database and updates tables and charts automatically. 

The script can be executed in Jupyter Notebook and Terminal environment. In order to successfully run the Python script, you need to configure your local database environment, which means either download and set up sequel pro or mysql. 

On sequel pro we have Zoe production database environment and all you need is to copy a local environment for that. The purpose of doing so based on the protection of our production database. The following steps give you a detailed instruction on how to acheive that.

# Download Sequel Pro 
- Go to https://sequelpro.com/download 
- Download the latest version of Sequel Pro 
- There's also useful documentation on their website pages for you to get a overview of Sequel Pro

# Connect Sequel Pro to Zoe Fin Database
- On the home page of Sequel Pro, choose SSH 
- The access to the production server you must use the credentials below:
  1. MySQL Host:127.0.0.1
  2. Username: query 
  3. Password: XYvRWAX4v3Nwt4.C
  4.Database: app_zoefin_production
  5.Port: 3306 (default port)   
  6.SSH Host: 18.218.10.77
  7.SSH User: query
  8.SSH Key: the key file(.pem) is attached to the email I sent to you 
  9.SSH Port: leave it as blank
  
 

