# chat

if you clone this projenct,
you have to install some packages.

1. Channels - ' python -m pip install -U channels '
2. docker/redis - *If you didn't install the docker, install the docker first.* ' docker run -p 6379:6379 -d redis:5 ' 
3. django channels access to redis - ' python -m pip install channels_redis '

if you want to test
1. python -m pip install selenium
2. python manage.py test chat.tests
