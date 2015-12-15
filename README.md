
How do I get started?
---------------------

1. Make sure you have Ruby 1.9.2 or later installed:

2. Download the application from GitHub

3. Install all required dependencies:

    $ bundle install

6. Initialize default local SQLite schema:

    $ rails generate active_record:session_migration
    $ rake db:migrate



Using the application
---------------------

In order to access AdWords data the application needs to be granted access by a
logged in user. You will be automatically redirected to a page with login prompt
when not yet authorized.

To grant access, click the 'Proceed' link. Make sure you are on the Google login
page, log in with your AdWords account credentials and select 'Grant access'.

Note: Granting access to the application will only allow access to the AdWords
data for the account. Other services will not be accessible.

Once logged in you can retrieve the accounts list, select an account and browse
the campaigns list or download a report with the corresponding menu items.
