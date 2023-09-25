# admitkart Otp Assignment
# Clone  repository
git clone (https://github.com/Gaurav-9810/admitkart.git)



### Step 2: Configure Backend
1.Navigate to the MobileOtpBackend directory:
cd MobileOtpBackend

2.Create a .env file in the root of the MobileOtpBackend directory and add your MongoDB connection URL. Replace <your-mongo-url> with your actual MongoDB URL:
MONGO_URI=<your-mongo-url>

3.In the userController.js file, located in the root directory of MobileOtpBackend, add your Twilio account details: accountSid, authToken, and twilioNumber. These details are required for sending SMS messages using Twilio.

Step 3:run npm i then Run the Backend
Start the backend server by running the following command in the MobileOtpBackend directory:
node index.js

Step 4: Run the React Project
1.Navigate to admitkart-frontend
cd ../
cd admitkard-frontend

2.Install the project dependencies:
npm install

3.Start the React project:
npm start

The React project should now be running, and you can access it in your web browser at http://localhost:3000/.


