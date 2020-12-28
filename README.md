# Django application for blogging

Check url: `https://djangoappforblogs.herokuapp.com/`

### Features:

1. Generate automatic user profiles when user registers and allow user to edit their profiles.
1. Allow users to edit or delete their blog posts.
1. Uses pagination with 5 posts per page.
1. Shows the latest post on top.
1. Allows to check all blog posts from specific user by clicking on their username.
1. Utilizes django class based generic views.
1. Allows to reset password through email link but currently working only for gmail users and the google app 16 digit password has to be manually stored in environment variable.

### To run the application on local machine:

1. Run the below command from terminal of your root directory to install requirements.

    ```sh
    $ pip install -r requirements.txt
    ```
1. Run django server.

    ```sh
    $ python manage.py runserver
    ```

1. Open application using url: `http://localhost:8000`.

### Future Work:

1. Adding connection to amazon s3 bucket to store data there.
1. Adding deployment through docker compose and kubernetes.
1. Using React.