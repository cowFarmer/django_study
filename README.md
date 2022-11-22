# Insta_clone
> 2022.11.19 ~ underway 

---

## Error log
---
2022.11.21
- templates/insta_clone/main.html을 만든 후 views.py, urls.py에서 main에 접속했을 때 나오게끔 유도하고 설정을 했는데, 다음과 같은 에러가 발생함.   
```
django.template.loaders.app_directories.Loader: /Users/hyeonho/project/insta_clone/venv_insta_clone/lib/python3.9/site-packages/django/contrib/admin/templates/insta_clone/main.html (Source does not exist)
```

해결하기 위해 search 하고 있음
---
2022.11.19
- zsh -> venv로 가상환경 및 django 설치 후 `django-admin startproject insta_clone` 커맨드 입력시 에러 발생하여 실행이 안됨   

__해결 방법__   
- bash로 django 설치 후 위 커맨드 입력하면 해결이 가능한걸로 보아, 환경 변수 설정의 차이가 있다고 파악됨
- m1 mac을 사용중인데, default shell을 zsh에서 bash로 변경 후 해결 완료