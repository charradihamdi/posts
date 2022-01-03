# posts
#to run application 
#________

-install virtualenv
#________

cmd : pip install virtualen
#________

-create newenv
#________

cmd : virtualenv newenv
#________

-activate newenv 
#________

cmd cd newenv/Scripts && activate
#________

run sever 
#________

python manage.py runserver 8000
#________

port : 8000
