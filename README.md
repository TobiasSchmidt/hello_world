# Installation & Requirements

Run  the following command on your terminal to add the repository to your Desktop

    $ git clone https://github.com/TobiasSchmidt/hello_world

Install Node.js and the npm package manager from the official site https://nodejs.org

Add npm to your repository's folder with the following command

    npm install
    npm init

Add the http-server library to test run a local webserver

    npm install http-server

Add this command to your test script in the package.json

    http-server .

after running this command in your terminal, you can test your application on http://127.0.0.1:8080

    npm test
    
# Application

Once you have everything setup, the website should great you with a nice welcome message 

![Alt text](application.jpg?raw=true "Application")
