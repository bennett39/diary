## 2019-02-12

**Streak** 20

**Today's Projects** Developed a barebones NodeJS server and router.
Luhn exercism problem in Python.

**Thoughts** I want to really drill down on NodeJS. I'll use my
portfolio site to do it.

I also want to low-key start working on interview prep problems. The
exercism problems are a good start, but I think HackerRank or LeetCode
are in the cards pretty soon to work on data structures and common
interview problems.


## 2019-02-11

**Streak** 19

**Today's Projects** Exercism - two JavaScript problems

**Thoughts** Been a few days since I wrote a journal entry. That's b/c
I've been kind of stuck in a rut on Stock Trader. I've also just been
busy with shabbat, debate judging, and personal/social life. It's no
excuse though! A journal entry literally takes 2 mins.

I have an autocomplete field that helps users find stocks now in Stock
Trader. It loads kind of slow though, because the data set of potential
stocks is so huge. Idk what to do about that.

I've also started trying to write tests for the application. It's
annoying though because all the documentation assumes I've set up my
application a certain way. I gotta dig into that more, but I've pulled
back for today at least to focus on other stuff.

Exercism was fun today and I learned some new JavaScript stuff. I always
learn a lot from looking at the community solutions.


## 2019-02-07

**Streak** 15

**Today's Projects** Stocktrader is fully implemented and live on
Heroku.

**Thoughts** It works! I'm excited about it. Now, I need to beef it up,
and add more functionality.

Ideas to take this to the next level:
- Lookup stocks by company name
- Graph of portfolio performance

The newly refactored code is much nicer than the old application.
Everything is separated out and I've cleaned up a lot of inefficiencies
and poorly named variables.


## 2019-02-06

**Streak** 14

**Today's Projects** Stock Trader - only a few TODOs left to implement.

**Thoughts** I've got Stock Trader working locally and deployed to
Heroku. Left to implement/port over from the old version are buy, sell,
profile, and nuke. Sessions and portfolio are all implemented.

I had to restart postgres when I restarted my VM. For future reference,
here is the command:

```bash
sudo /etc/init.d/postgresql restart
```

Forgot to do my log yesterday, but that was the big coding day. Today
I've been mostly writing. Only a little bit of code.


## 2019-02-04

**Streak** 12

**Today's Projects** Flask-Sqlalchemy engine and models created.
Implemented several queries as part of refactor. Will work on exercism
later tonight.

**Thoughts** SQLAlchemy models and queries seem easier to integrate and
manage than the SQL queries I wrote originally. They also work
seamlessly across local development and remote production environments.
The challenge is learning a completely new syntax for writing my
queries that ends up getting translated to SQL commands.

It has been a lot of frustrating trial and error, but I'm starting to
get the hang of how SQL Alchemy engines, sessions, and QueryObjects
work. Once I start churning out these queries, implementing the rest of
the application should be fairly easy. Just need to test it regularly
along the way.


## 2019-02-02

**Streak** 10

**Today's Projects** Postgres runs locally, now. Upgraded to version 10.
Heroku test project works locally and on Heroku connecting to the
database via SQLAlchemy.

**Thoughts** I'll need to refactor my whole application to get it
working because CS50 had me write the queries straight in SQL via the
execute() method. Queries get returned as objects and I'll need to
completely rethink how everything gets iterated and called.

I can build it--but it might be easiest to do it from scratch,
unfortunately.


## 2019-02-01

**Streak** 9

**Today's Projects** Trying to deploy my stock picker app to Heroku --
the app works locally but doesn't play nice with Postgres.

**Thoughts** REALLY frustrating trying to get these legacy projects
deployed. I think I've given up because it would basically require
rewriting the whole app. I might do that at some point, I'm just
frustrated at the moment and done with coding for the day.

The last thing I did today was build a small proof of concept app. It's
possible to get a Flask app working with Heroku Postgres. It's just not
possible the way my stock picker is currently structured.


## 2019-01-30

**Streak** 8

**Today's Projects** Budget app up and running with database and Flask
server. One exercism problem.

**Thoughts** Realized I was making this harder than it needed to be by
creating a new Django project. I went back and restored the Flask
version of Budget. It's now running and I'm having success refactoring
certain parts of it.

Writing tests for Flask is confusing though. I need to do it, so that's
a next step. I'll also need to figure out how to deploy Flask with WSGI.

I think for my portfolio, I might use the stock trading game I developed
for CS50. Especially if I can get some nice data viz, design, session
management. The lessons I learn from this Flask project can help there.


## 2019-01-29

**Streak** 7

**Today's Projects** Two more exercism solutions. A little work on
budget, not much. And a PR to SongPro bc I saw Brian tonight.

**Thoughts** Tonight's Carbon 5 hack night was a much higher caliber
meetup than the Brooklyn one. This was mostly professional developers
working on stuff. I'd like to get to know these people better.

One person said they hadn't heard of anyone using Django in a few years.
I don't want to let that dissuade me, but I think I should try to wrap
this budget app up quickly. Or, build something different in Django,
like the stock trading game I made for CS50.

(See more recent entries, I've accelerated the timeline on the budget
app.)

## 2019-01-28

**Streak** 6

**Today's Projects** Exercism refactoring and one solution submission.
Get sample data for budget app.

**Thoughts** I have coded the past two days, I've just forgotten to
write a journal

On Saturday, two days ago, I got the personal capital authentication
working on my Django app. The session persists across redirects as you
enter your two-factor authentication code.

On Sunday, I defined the database schema in `models.py` while I was at
Hacker Hours.

At this point the budget app is coming along, but I'm not looking
forward to making the JSON file play nice with the database. Seems like
that might be tricky, and I'll need to do some reading on how best to do
that in Django.


## 2019-01-25

**Streak** 3

**Today's Projects** Add Postgres to Heroku for budget app. Write blog
post about Postgres on Heroku. One Exercism exercise. Read two chapters
of You Don't Know Javascript.

**Thoughts** I like writing about the things I'm learning. It helps
solidify what I'm doing. However, it feels slow. I could have written a
lot more code today if I hadn't been writing about the code I did
commit.

I'm committing to JavaScript pretty heavily. Seems like if I want to do
anything web related I need to be ready to write JavaScript, so I want
to get into the the nitty gritty and feel very comfortable with it. The
syntax is familiar feeling. I learned it on freeCodeCamp last year, but
it's also a nice mashup of C and Python -- syntax-wise.

I now know that variables in JavaScript aren't typed. Instead, the data
inside of a variable has a type. The data in a variable can change if
that variable is declared using `var` or `let`.

I have a basic understanding of prototypes and prototypal inheritance. I
also have a basic grasp on closures and scope. Those are two areas I'll
definitely want to dig into.

Exercism is moving slowly. Perhaps it's a good pace for me though. I can
focus on my portfolio projects and switch to really drilling interview
prep once my portfolio projects are done.


## 2019-01-24

**Streak** 2

**Today's Projects** Two more exercism problems. Finally getting my
command line working the way I want it to.

**Thoughts** I'll probably code more today, but wanted to go ahead and
write my daily log.

I was getting frustrated with debugging javascript from the command
line, but I found that node will run javascript files `$ node file.js`
and the exercism test suite using `npm test` also prints out any
`console.log()` calls.

I'd like to start on my big projects today. Maybe get the barebones
Django up and running on my budget app. I already have a lot of the
backend stuff for that one figured out since I built it before. Now, I
just need to port it to Django and refresh my memory on the Personal
Capital API.

## 2019-01-23

**Streak** 1

**Today's projects** Writing about React, setting up command line
config, starting `exercism` repository.

**Thoughts** I was starting to get annoyed with the format of the
100DaysOfCode journal. I also recently wiped my installation of Linux
and am starting fresh with a new Crouton CLI.

New project: dive into JavaScript via exercises on exercism. My thoughts
on my path moving forward:

- Get good at JavaScript, learn trivia for interviews
- Practice on LeetCode and exercism in JavaScript & Python for
  interviews
- Rebuild my budget app with dummy data for someone to log in. Then, use
  Vue to render it, a JS library for data viz, automatic updates with
  Airflow, and some type of session managment like Redis. Use a Django
  backend for rapid development.
- Redo my portfolio using Gatsby.js
- Build a Sudoku site with tons of puzzles created in React, a solver
  that shows answers or gives hints, and sessions so users can track how
  many puzzles they've solved and their best times (maybe with OAuth
  through other logins like Google?). This would be a NodeJS backend and
  some type of simple data store for user sessions.
