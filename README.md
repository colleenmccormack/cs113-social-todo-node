# CPSC113 Social todo app

Thank you, Kyle, for the starter app. It was incredibly helpful!! (I totally did use it and am just changing the README.md file.)

## How to run this

My URL for testing purposes: "[https://cmm244-social-todo-1.herokuapp.com/](https://cmm244-social-todo-1.herokuapp.com/)"

Get the repo

    git clone https://github.com/colleenmccormack/cs113-social-todo-node
    cd cs113-social-todo-node

Install the dependencies

    npm install

You'll need to start MongoDB somewhere to store data. And, you'll need to
choose a secret for signing browser cookies.

You can run the server with something similar to

    PORT=5000 SESSION_SECRET='sdf' MONGO_URL="mongodb://localhost:27017/social-todo" ./node_modules/.bin/nodemon index.js

where your values of `PORT`, `SESSION_SECRET`, and `MONGO_URL` could be different.
If you are on Cloud9, don't set `PORT`. `SESSION_SECRET` can be whatever you
want.


