# react_django_http_tutorial
멋쟁이사자처럼 React Django HTTP 통신 정리본입니다.

## 이전 세팅
### React:
```
npx create-react-app react_tutorial # React 프로젝트 생성
yarn add axios # axios 설치
```

### Django:
```
pip install django # Django 설치
pip install djangorestframework # DRF 설치 
pip install django-cors-headers # CORS 방지
django-admin startproject django_tutorial # Django 프로젝트 생성
```

### Django Settings:
```
asgiref==3.5.2
Django==4.0.5
django-cors-headers==3.13.0
djangorestframework==3.13.1
install==1.3.5
pytz==2022.1
sqlparse==0.4.2
```

## Frontend와 Backend 통신
![image](https://user-images.githubusercontent.com/86935465/175817947-44073426-c70b-4c54-9d44-dab357356dd8.png)
