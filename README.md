### Housing Location Finder
A simple Angular application that displays housing locations and allows users to filter by city.

# Features
- View a list of available housing locations.
- Filter locations in real time by city.
- Click on a housing location to view details.
-  Uses a fake backend (JSON Server) to serve housing data.

# Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/asl1n/Housing.git
cd Housing

2️⃣ Install Dependencies
Make sure you have Node.js and Angular CLI installed, then run:
npm install

3️⃣ Install JSON Server
npm install -g json-server

4️⃣ Start the JSON Server
Make sure db.json is inside your project folder. Then, run:
json-server --watch db.json --port 3000
This will start a local backend at http://localhost:3000/

5️⃣ Run the Angular Application
In a new terminal window, start the Angular app:
ng serve
