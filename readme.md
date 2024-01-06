
docker-compose build
docker-compose up
docker-compose run --rm web-app sh -c "python3 manage.py migrate"


