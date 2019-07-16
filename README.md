# image_storage

Near manage.py   
```redis-server``` - to run redis server
```celery -A images_storage worker -l info``` - to run worker
```celery purge -A images_storage``` - clean queue


'''python manage.py createsuperuser''' - create superuser django

'''heroku ps:scale worker=1'''
'''heroku ps:scale web=1'''