# Omnifood

Landing page website for a fictional food delivery company called **"OMNIFOOD"** built using modern **HTML5**, **CSS3**, and **JavaScript**.  
![Live project](project.png)

*This project is a part of a Udemy course taught by Jonas Schmedtmann.*

---

## 🚀 How to Run This Project

You can run this project locally using **Docker**. It uses **Nginx** to serve the static files.

### 🐳 Run with Docker

#### 1. Clone the Repository

```bash
git clone https://github.com/chinu0/Omnifood.git
cd Omnifood
#run this command
docker build -t omnifood-site .
docker run -d -p 8080:80 omnifood-site
