## Portfolio Homework Assignment 1
###Introduction

This is my submission for homework assignment 1:
https://github.com/RutgersCodingBootcamp/04-16-NB-Class-Content/blob/master/homework-assignments/week-1-html-css/recommended-homework-assignment.md

I decided for this project, to write the CSS from scratch. I did another version of this assignment with Bootstrap: You can find it here:

https://github.com/arnold-lei/portfolio-

For this assignment I found that I was a little rusty with CSS and it was really good practice to write the whole thing myself. There are still many things I need to learn. Part of the challenge of this assignment was to try to replicate the screenshots exactly. I took some liberties with ceartain styles but I remained as close to the original designs as possible. I mostly changed the font and text sizes. 

### Challenges

#### Footer:
The footer was paticularly challenging. I tried for a very long time to do it with pure CSS but I felt like I was getting no where with it. I tried a lot of tutorials on line but I still can't figure it out. For some reason the container div doesn't reach the bottom of the page.

I FINALLY FIGURED IT OUT!!! I'm not sure why the container for this website wasn't extending to the bottom no matter what I tried. Finally I tried setting the div I wrapped the whole site in as "position:absolute;" and then the container for the site content as "position:relative;" and then the footer to "position:absolute; bottom:0;" 
 
#### Sizing:
The sizing of the panels. I tried to make the website work with the specified dimensions for the hwk but I ended up ditching the width of the outer container. I prefer the extra space between the main content area and the social media panel. I used width percentages to accomdate for different screens and monitor sizes.

##### Heroku:
This website can be found hosted on heroku here:
http://arnold-lei-rcb-portfolio.herokuapp.com/index.html

Hit a little snafu, I changed the project name in Heroku dashoboard and I didn't change it on CLI. So when I tried to push it to Heroku it didn't find the app name. I googled around and found this solution:
https://devcenter.heroku.com/articles/renaming-apps#updating-git-remotes

#### Responsive Web Design
I've always wanted to learn how to do repoonsive webdesign and I finally got around to reading about it. It's more simple that I had expected. I am still trying to figure out how to create a mobile nav.

I realize now why bootstrap uses ul li for their nav. I got it working like a charm now. There are still some bugs with the portfolio page.

### Things I Learned
I think that my biggest take away is how to create a sticky footer from scratch. It was harder that I expected. For the life of me I could not get the container to go the length of the website. In terms of CSS and HTML I was more diligent about writing comments to make the code clearer knowing that my professor would look at it ;) 

I'm not new to Git but I think this time around I'm really starting to understand Git. Instead of just typing the code I'm taking the time to understand that commands. Having someone explain them to me has been really benificial as well. I've tried to be very clear with all my commit comments and making sure that I write at least something useful for just in case I need to go back to an older version. 

