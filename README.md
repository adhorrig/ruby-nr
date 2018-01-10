This is a simple blog application with CRUD functionality and New Relic enabled for monitoring.

To get started;

* Ensure you have Ruby and Rails installed.
* Clone the repository. `git clone https://github.com/adhorrig/ruby-nr.git`

Once the project has been cloned, you will need to install the gems;

* `bundle install`

Afterwards, you will need to migrate the database by running;

* `bin/rails db:migrate`

Finally, you will need to enter a New Relic license key into `config/newrelic.yml`. This will allow the data to report into your account.

You can then run the project with;

`bin/rails server`
