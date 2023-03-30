# Build


```sh
$ docker-compose up -d
```

# Stop

```sh
$ docker-compose stop && docker-compose rm -f
```

docker exec server psono 

create user 
```sh
$ python3 ./psono/manage.py createuser username@example.com myPassword email@something.com
```
promote user 
```sh
$ python3  psono/manage.py promoteuser username3@127.0.0.1 superuser
```

