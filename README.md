# hello_world

Run $ git clone https://github.com/TobiasSchmidt/hello_world on your terminal to add the repository to your Desktop

Install Node.js and the npm package manager from the official site https://nodejs.org

Run the following commands in your repository's folder

    npm install
    npm init

Add the http-server library to test run a local webserver

    npm install http-server

Add this command to your test script in the package.json

    http-server .

after running this command in your terminal, you can test your application on http://127.0.0.1:8080

    npm test