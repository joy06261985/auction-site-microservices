# Auction Site Project_ Timepiece Traders

This project is an implementation of an auction site, modeled on eBay. The application allows users to interact with various auction functionalities, manage user accounts, and handle admin and database operations efficiently. Group project for MPCS Topics in Software Engineering.

Architecture:

<img width="1009" alt="Screen Shot 2023-12-13 at 10 56 54 AM" src="https://github.com/esegerberg3112/auction-site/assets/61920056/b9cce8c6-ade6-49b7-b980-f5114ab0c16a">

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- Python with Flask
- RabbitMQ
- Docker
- MySQL
- Redis


## Technology Stack
**Frontend:**
- Node.js for serving the website  
- Express.js for the API Gateway  
- ReactJS / HTML / CSS for website pages  
**Backend:**
- Python - Flask  
- RabbitMQ for microservice communication  
**Databases:**
- MySQL - hosted in separate Docker containers (accounts, items, notifications, auctions)  
- Redis - hosted in Docker container (bidding)  


## Features
- Frontend Functions
  - User account management (create, delete, suspend, login, logout)
  - Auction interactions (see active auctions, add item, bid on item, remove item, purchase item)
- Database Functions
  - Persistent data storage
  - Data retrieval for frontend and backend services
  - CRUD operations on data
- Admin Functions
  - Auction and user management (stop auction, remove/block user, modify categories)
  - View and sort auctions
  - Examine metrics and customer support emails
- Auction Functions
  - Listing, bidding, categorization, and searching of items
  - Watchlist and notification features
  - Shopping cart and checkout functionalities
- User Functions
  - New user creation, user updates, and account suspension
  - Item management (list, update, flag, categorize, delete)
  - Bidding and auction participation


### Installation
1. Clone the repository to your local machine:

```bash
git clone https://github.com/joy06261985/auction-site-microservices.git
cd auction-site-microservices
```
2. Install the necessary Python packages:
```bash
pip install -r microservices/requirements.txt
```
3. Start Docker Desktop on your local machine.
4. Build the Docker containers
```bash
docker-compose build
```
5. Start the application using Docker Compose:
```bash
docker-compose up
```
6. In a separate terminal window, run the start-up script:
```bash
bash start_application.sh
```
7. Access the application in your browser at [http://localhost:3000]



## Authors
Cole Spruyt  
Ashkan Rohani  
Eric Segerberg  
Thomas Lee  
Loay Al Rashdi  
Chen Hui (Fei) Wang  
