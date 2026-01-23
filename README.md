# Instructions for running in dev mode
- npm i
- npm start
- navigate to http://localhost:5173/ 

## Bug Log
- I ran into an issue using the Google API in my local env. I resolved this issue by adding http://localhost:5173/  to the listed of trusted websites within the Google Cloud console.

## Setting the API Key
In order to run this program, a google API key must be provided. This key can be obtained by ..... XXXXXX.

With your new key, locate the .env file. Replace "YOUR API KEY," keeping the quotation marks.

## Installs
1. Install necessary libraries/packages (including: node,npm)
```pip install <package>```

## Windows
To run on windows, I managed the node dependencies by using docker. Following this guide's code:
'https://nodejs.org/en/download/'.

### Using Docker
1. docker and docker gui installed
2. created docker file
3. build the image
'docker build -t <dropletName> .'
current name: getting-started'
4. run the image
'docker run -d -p 127.0.0.1:3000:3000 getting-started'
5. view on port 3000, http://localhost:3000/