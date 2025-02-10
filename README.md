🚀 ***Dockerized Web Scraper with MySQL Integration***
📌 *Project Overview*
This project demonstrates how to build a Dockerized Web Scraper using Python that extracts movie quotes from a website and stores them in a MySQL database. The entire setup runs inside Docker containers, ensuring portability, scalability, and seamless deployment across different environments.

🔎 ##**Features**
✅ Automated Web Scraping with requests & BeautifulSoup
✅ Containerized MySQL Database for structured data storage
✅ Custom Docker Network for seamless container communication
✅ Scalable & Reproducible Setup – Run anywhere with a single command
✅ Dependency-Free Deployment with Docker Compose


🛠️ **Tech Stack**
Python 🐍
Docker & Docker Compose 🐳
MySQL 🗄️
BeautifulSoup (for web scraping)
requests (to fetch web content)
mysql-connector-python (to interact with MySQL database)

🚀 **Getting Started**
🔹 Prerequisites
Ensure you have the following installed on your machine:
✅ Docker 🐳
✅ Docker Compose
✅ Basic knowledge of Python & MySQL

📌 Future Enhancements
🔹 Scrape data from multiple websites
🔹 Add API integration for real-time data retrieval
🔹 Implement a data visualization dashboard

**SQL commands**

docker run -d --name mysql-container -e MYSQL_ROOT_PASSWORD=redhat -e MYSQL_DATABASE=scraper_db -p 3306:3306 MySQL:latest
This command will:
Start a MySQL container named mysql-container
Set the root password to redhat
Create a database named scraper_db
Expose MySQL on port 3306

Access MySQL & Create Table

docker exec -it mysql_container mysql -u root -predhat

USE scraper_db;

CREATE TABLE quotes ( id INT AUTO_INCREMENT PRIMARY KEY, text TEXT NOT NULL, author VARCHAR(255) NOT NULL);



💬 Feel free to reach out for collaboration, feedback, or discussions on Docker, Web Scraping, and Data Engineering!

🔗 GitHub: https://github.com/TejPATHAK
🔗 LinkedIn: https://www.linkedin.com/in/tejaswi-pathak/
