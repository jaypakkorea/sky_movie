# Readme



### Getting Started



final_pjt_back

* `python -m venv venv`
* `source venv/Scripts/activate`
* `pip install -r requirements.txt`
* `python manage.py runserver`



final_pjt_front

- npm install
- npm run serve





### API

## 6) API 설계



| HTTP verb | URL패턴     | 설명                         |
| --------- | ----------- | ---------------------------- |
|           | `movies/`   | include('movies.urls')       |
|           | `profile/`  | include('accounts.urls')     |
|           | `accounts/` | include('dj_rest_auth.urls') |







### 폴더 구조 



#### back

전체 프로젝트 폴더 : **django_final**

영화 추천 및 커뮤니티 전체 app : **movies**

계정 app : **accounts**

프로필 사진 저장 폴더 : **media**

