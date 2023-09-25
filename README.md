# admitkart
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

Usage
Describe how to use your project or any other relevant information.

License
This project is licensed under the [License Name] License - see the LICENSE.md file for details.

Acknowledgments
Mention any libraries, frameworks, or tools used, and give credit to their creators if necessary.

Please ensure that you have the correct MongoDB connection URL, Twilio account details, and any other necessary configurations for your project. Users who clone these repositories can follow these instructions to set up and run the project successfully.
