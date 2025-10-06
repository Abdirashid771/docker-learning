🐳 Flask + Redis Multi-Container App

A simple project to learn Docker Compose by running multiple containers — one for a Flask web app and another for a Redis database.

🚀 What It Does
Flask web app has two routes:
/ → Welcome message
/count → Increments and shows a counter stored in Redis
Redis stores the visit count.
⚙️ How to Run
# Clone the repo
git clone https://github.com/Abdirashid771/docker-learning.git
cd docker-learning

# Start the app
docker-compose up


Then visit:

http://localhost:5000
http://localhost:5000/count

To stop:

docker-compose down