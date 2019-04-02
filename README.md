# Products catalog

Products catalog is a Rails project built using [VueJS](https://vuejs.org/) as frontend framework.

## Notes

* Make sure you have postgresql up and running
* Make sure you have yarn installed ( we use [asdf](https://github.com/asdf-vm/asdf) as version manager )

## Development Setup

1. Clone the repo:

        $ cd ~/projects
        $ git clone https://github.com/nebulab/products_catalog_bootstrap.git
        $ cd products_catalog

2. Install dependencies and prepare database:

        $ bundle install
        $ yarn
        $ bundle exec rails db:create

3. You're up and running. Just start the app as usual:

        $ bundle exec rails s
        $ ./bin/webpack-dev-server

4. Navigate the application locally:

http://localhost:3000

## Result!

![image](https://user-images.githubusercontent.com/9986708/55412038-fe1f4c80-5566-11e9-8a34-e3c339aa38c2.png)
