# Ruby on Rails Tutorial sample application

Twitter-like application built following
Michael Hartl's [Ruby on Rails Tutorial](https://www.railstutorial.org/book).

## Demo

View live demo at: https://kv-rails-tutorial.herokuapp.com/

## Run Locally

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```