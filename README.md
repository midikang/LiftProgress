# Rails5 application template
Based on rails 5.0.0.1

Created by Midi Kang(midi13@gmail.com)

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

```
rails g react:install
```

https://medium.com/coding-and-web-development/creating-a-resource-for-lifts-d9c5135489b1#.o1otfysqc

```
rails g resource Lift date:date liftname ismetric:boolean weightlifted:integer repsperformed:integer onerm:integer
```

```
rake db:create db:migrate
```

```
rails c
```

Add a new Lift to the database with this command:
```
Lift.create date: Date.today, liftname: 'Bench press', ismetric: true, weightlifted: '220', repsperformed: '1', onerm: '220'
```
