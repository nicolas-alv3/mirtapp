# template-kotlin-postgres4heroku

This template was made for a backend app developed in kotlin with maven,hibernate and postgresql database.

## To use it

- Change the database URL in the `application.properties`

## To create heroku app

- `heroku login`
- `heroku create my-app`
It will create a new heroku app with a heroku remote URL. Then do
- `git push heroku master`

### If running the main app raise an error, try removing `&serverTimezone=UTC` from the Database URL.

## Happy hacking:D
