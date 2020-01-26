# Petstagram :cat: :dog: :rabbit: :mouse: :snake:


Makers Academy weekend challenge: build an Instagram clone using Rails. Instructions: you'll need users who can post pictures, write comments on pictures and like a picture. Style it like Instagram's website (or more awesome).

## Installation
* Clone this repo
* Run bundle install from the command line
* Run bin/rails db:create and then bin/rails  db:migrate from the command line

## Testing
* Run bundle exec RSpec from the command line

## Using this app

* Run bin/rails server and visit http://localhost:3000

## User Stories

```
As a animal lover
So that i can see cute photos of animals
I would like to sign up for an account on Petstagram

As a user
So that I only need to sign up once
I would like to be able to login to my existing account.

As a pet owner
So that I can share pictures of pets
I would like to be able to post a picture to Petstagram

As a user
So that I can share my opinions on other people's cute pets
I would like to be able to comment on other pictures.
As a user

So that I can share my appreciation for cute pets
I would like to be able to like pictures.
As a user

So that I can change my mind
I would like to be able to unlike pictures I have liked.
```

## What I learned from this challenge

* A deeper understanding of how the Rails MVC model works, and how Rails models, views and controllers interact with each other.
* I have a better understanding of Active record migrations, and validations
* How the devise gem and paperclip works - gem I had not used before.
* Practice with continuous  integration with Travis CI and how to set this up and use in my project.



## What I would like to fix/improve
* I would like to add the feature where users can delete or update their comments/posts
* I would like to improve the visual output of my program
