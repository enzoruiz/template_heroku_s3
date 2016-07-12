# template_heroku_s3
Django template for deployment in Heroku with database in postgresql and static files in Amazon S3

## How to Use

To use this project, follow these steps:

1. Install all the requirements (pip install -r requirements.txt).
2. Set AWS variables: AWS_STORAGE_BUCKET_NAME, AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY.
3. Set database parameters.

## Deployment to Heroku

    $ git init
    $ git add -A
    $ git commit -m "Initial commit"

    $ heroku create name-of-my-app
    $ git push heroku master

    $ heroku run python manage.py migrate