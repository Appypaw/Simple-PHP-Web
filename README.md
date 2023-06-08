# Simple-PHP-Web

Simple PHP Web Application for AWS elastic beanstalk.

This is a simple PHP web application designed for deployment using AWS Elastic Beanstalk. It showcases the integration of Elastic Beanstalk with AWS RDS for MySQL, allowing you to store and retrieve data from a managed MySQL database.

Put the PHP and CSS files together in a single folder excluding the SQL file and Make .zip whatever you like and deploy them on Elastic Beanstalk.

I've converted the CPU benchmark data CSV file obtained from https://www.userbenchmark.com/page/developer into SQL format. I changed the column name "Rank" to "Ranking" because "Rank" is a reserved word in MySQL. Similarly, I used backticks (`) to handle the identifier for the column name "Type" since it is also a reserved word.
