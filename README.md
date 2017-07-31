# Logs-Analysis Project
This is a project assigned by Udacity in part of the Udacity Full Stack Nanodegree program. In This project, we're provided a sql file to generate a `PostgreSQL` database and a `Vagrantfile` settings to run a VM server to run the database.

We need to answer the following questions by writing queries for the database and outputs the result onto a text file `log-report.txt`:  
1. What are the most popular three articles of all time?  
2. Who are the most popular article authors of all time?  
3. On which days did more than 1% of requests lead to errors?  

## Usage
• Download and install VM using [VirtualBox](https://www.virtualbox.org/wiki/Downloads)  
• Download and install [Vagrant](https://www.vagrantup.com/downloads.html) for the VM settings   
• Run in the working folder `vagrant up` to configure the VM  
• Run `vagrant ssh` to log into the VM  
• Download the [news data](https://d17h27t6h515a5.cloudfront.net/topher/2016/August/57b5f748_newsdata/newsdata.zip)  and save it in the working VM folder  
• Run `psql -d news -f newsdata.sql` to generate the database  
• Run `python reporting.py` in terminal to generate the database report
