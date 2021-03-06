# conference
# Twilio Node.js app for generating an access token
This will guide you through generating an access token for Twilio using Node.js.
## Prerequisite

- This project requires that you have Node.js installed on your system. You can install [Node.js](https://nodejs.org/) here if you don't have it installed.
- You need a Twilio API KEY. Get it [here](https://twilio.com/)

## Setup

- Clone the repository to your system by running the command:

```sh
git clone https://github.com/sairamsunkara673M/Conference
```

- cd into the project folder and install all packages:

```sh
  cd TwilioNodeServer && npm install
```

- Create your configuration file:

```sh
   cp .env
```

- Next, open up `.env` file in your editor and update your Twilio API KEYs.

```
TWILIO_ACCOUNT_SID=TWILIO_ACCOUNT_SID  # Your Account SID
TWILIO_API_SID=TWILIO_API_SID # Your API Key SID
TWILIO_API_SECRET=TWILIO_API_SECRET # Your API Key SECRET
```

Run the app

```sh
  node app.js
```

- If everything goes fine, Node.js server will be running on: `http://localhost:3000/`

## Example use case

To generate an access token, visit http://localhost:3000/token?identity=sairam

In the case, `sairam` is the identity of the user we want to generate an access token for.

# A demo Video chat app using Vue.js
   
## Prerequsite

To run this project, you need to have:

- [Node.js](https://nodejs.org/) installed on your system
- A server for generating a token. Clone and install it [here](https://github.com/sairamsunkara673M/Conference).

## Setup

cd into the project:

``` bash
cd VueVideoChat
```

Install dependecies:

``` bash
npm install
```

Run the app!

``` bash
npm run dev
```

The app should now be accessible from http://localhost:8080

And that's it. You can read more about how it was built [here](https://blog.twilio.com)

# conference with socket.io library in python.

Implemented Conference with socket.io library using Python

## Setup

cd into the project:

``` bash
cd Conference_with_socket.io

# Prerequsite

Install these packages "socket, cv2, pickle, struct, imutils"

``` bash
pip3 install opencv-python
pip3 install imutils
```
# Run

``` bash
python3 server.py
python3 client.py
``` 