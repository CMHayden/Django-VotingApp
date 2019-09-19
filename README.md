# Django-VotingApp
**Version 1.0.0**

This project was completed to help me to learn the Django framework, and practice some python.

The idea is to use django and sqlite to create an app for voting. It can be divided into two parts, the admin side and the user side.


## Admin side

The admin side allows users to log in as an admin displaying a dashboard with options. Currently, it allows the admin to modify a question, it's choices, delete a question, add a new question, add choices to any question, and create new users.

## User side

The user side allows users to see the 5 most recent polls. The user can also check the results of the poll and vote on a poll.

# Getting started

To run this application, firstly you must clone it. Once cloned, using your cmd, CD into the cloned folder. If needed, install pip and pipenv.

Once all is installed, simply run the commands:
```console
Callums-MacBook-Pro-6:flask-guestbook callumhayden$ pipenv shell
(Django-VotingApp) bash-3.2$ pipenv install django
(Django-VotingApp) bash-3.2$ python manage.py runserver
```
This should display the application on localhost port 8000.

## Contributing

Interested in contributing to this guestbook? I'd love to hear any suggestions on what to improve, any contributions you can make, and any feedback on the project. Please feel free to create [a new issue with your ideas](https://github.com/CMHayden/Django-VotingApp/issues/new) and I'll be in touch asap.
