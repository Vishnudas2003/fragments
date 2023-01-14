# fragments

# CCP first lab

# INSTRUCTIONS ON HOW TO RUN VARIOUS SCRIPTS FOR LAB 1

# lint

npm install --save-dev eslint
npx eslint --init

or

npm init @eslint/config
"lint": "eslint --config .eslintrc.js src/\*\*"

# start

npm start
"start": "node src/server.js"

# dev

npm run dev
"dev": "LOG_LEVEL=debug nodemon ./src/server.js --watch src"

# debug

npm run debug
"debug": "LOG_LEVEL=debug nodemon --inspect=0.0.0.0:9229 ./src/server.js --watch src"
