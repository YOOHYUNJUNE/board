- 프로젝트 생성, 앱 생성
```bash
django-admin startproject <name>
django-admin startapp <name>
```

- 나머지
```bash
python manage.py <command>
```



## HTTP status code
- 200 : OK
- 30X : redirect
- 4xx : client error
    - 401 : unauthorized 
    - 403 : forbidden
    - 404 : not found
- 500 : server error