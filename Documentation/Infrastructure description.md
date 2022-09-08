Like in the ..\Screenshots\ArchitectureDiagram file 
where it explains the infrastructure of the System.

the System consists of: 

1- base code in the GitHub repository, when pushing any changes it will

2- Circle CI starts in progress where it will build the code and test it, then deploy it to 

  3- AWS Elasticbeanstalk has 

    4- RDS that has the 
    5- Postgres Database initialized on it. 
AWS Elasticbeanstalk represents the webserver to run the API on it, and 

6- AWS S3 where has bucket that use to store the static files like images, CSS and HTML files, that will be used by the end user/ clients.  
