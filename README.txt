first install dependencies 
npm install

to start the server
node app.js

to add new blogs in the url navigate to /compose
ex. localhost:3000/compose

to search for posts /posts/:postName
ex. If on the home page i have a post with a title Day 1 
    i would then navigate to localhost:3000/posts/Day-1 

*the post title does not have to match exactly as it uses
lowdash to make format the search input when searching for
the post, in the example given above the user could also type
localhost:3000/posts/day 1 
and it would still find the post
