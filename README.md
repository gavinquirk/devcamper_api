### Devcamper API Installation Instructions

1. Clone repository into a local folder
2. Run "npm install" in the root folder to install dependencies
3. Create a config.env file in the config folder, and fill in required variables  
   ..._ NODE_ENV= (environment type)  
   ..._ PORT= (Port number)  
   ..._ MONGO_URI= (Mongo DB connection string)  
   ..._ GEOCODER*PROVIDER= (Geocoder provider for node-geocoder package)  
   ...* GEOCODER*API_KEY= (API key from geocoder provider)  
   ...* FILE*UPLOAD_PATH= (File path to public/uploads folder)  
   ...* MAX*FILE_UPLOAD= (Maximum file upload size)  
   ...* JWT_SECRET= (Secret string used in password encryption)  
   ...\* JWT_EXPIRE= (Expiration time for JWT)

### Server start and other scripts

1. "npm start": Start the server
2. "npm run dev:" Start the server in development mode
3. "node seeder -import": Seed database with placeholders
4. "node seeder -delete": Delete all records from database"
