# SpringBootVueApplication
<h3>Requierements</h3>

Python 3.5 https://www.python.org/downloads/

Node.js https://nodejs.org/en/download/

Yarn https://yarnpkg.com/en/docs/install#windows-stable

<h4>If missing, install with your terminal:</h4>

    pip install httpie
    
    yarn global add @vue/cli@3.1.5
    
    yarn add axios@0.18.0 vuejs-logger@1.5.3
    
    yarn add @okta/okta-vue@1.0.7
 
    npm install --save vuejs-logger
    
    npm install --save axios
    



Create a free Okta account  https://developer.okta.com/

<h4>Change value client_id with your ClientID from Okta</h4>

SpringBootVueApplication\client\src\router.js

    client_id: 'YourOktaClientID',

SpringBootVueApplication\server\src\main\resources\application.yml

    clientId: 'YourOktaClientID'
  
   
<h4>Run</h4> 
In a terminal go to your server directory ( …..\SpringBootVueApplication\server)  
 
    gradlew bootRun


And
Another terminal go to your client directory ( …..\SpringBootVueApplication\client)

    yarn serve


and go to http://localhost:8080.
