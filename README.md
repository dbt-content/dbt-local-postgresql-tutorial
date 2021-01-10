
### Welcome to this dbt project following dbt tutorial for a local PostgreSQL DB

This repository is for local tests on PostgreSQL with dbt tutorial tables (Customers, Orders and Payments). CSV source files for these tables are in [data](https://github.com/victorcouste/dbt-tests/tree/master/data) directory.


### Using these starter projects

For the local project (master branch):
- Create your local db profile on your local PostgreSQL (example in [postgres_profile.yml](https://github.com/victorcouste/dbt-tests/tree/master/postgres_profile.yml)) and copy it in your local `~/.dbt/` directory.
- Upload samples data with `dbt seed` command.


Then try running the following commands:
- dbt debug
- dbt list
- dbt test
- dbt run
- dbt compile
- dbt snapshot
- dbt docs generate


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](http://slack.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
