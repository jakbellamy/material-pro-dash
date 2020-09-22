#CHECK IT OUT

It's Material-UI's paid template. I've been using this for work and I think it's great.

Best use case (in my opinion): <br>
Just take the stuff you like and delete around it.

##Getting Started
`npm i` --> install dependencies <br>
`npm start` --> start her up<br>
`npm run build`  --> Builds

##Deploy
I found that to deploy to Heroku, I had to change the start script. Here's what I did.
````
...
  "scripts": {
    "start": "serve -s build",
    "dev": "react-scripts start",
...
````
If you go this route, just change your normal development routine to typing <br>
`npm run dev` rather than `npm start`
