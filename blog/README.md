# ReactJs_Blog
Creating a blog website in react js with third party api integration

# Getting Started with Create React App

### `npx create-react-app blog`.
### `cd blog`
### `npm init`
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

## NPM Installed In the Project
1. For the Router to navigate between pages we need the following library
### `npm install react-router-dom`

2. For running the third party API, have installed "Axios", libraries for the same can be installed by
### `npm install axios`

3. Have also used an NPM Library for Twitter API 
### `npm install --save react-twitter-embed`

# NOTE: (Warnings received)
You may recieve a Error 429() <br />
This error occurs when we hit the 3rd party api multiple times in a short period of time.
## Error message may read
`code: 	 "rateLimited"
message: "You have made too many requests recently. 
	  Developer accounts are limited to 100 requests over a 24 hour period 
	  (50 requests available every 12 hours). 
	  Please upgrade to a paid plan if you need more requests."
status:   "error"`
