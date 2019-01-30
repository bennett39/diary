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
