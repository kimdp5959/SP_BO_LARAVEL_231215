# 테스트용

SP_BO_LARAVEL_231215  
Laravel v10.37.3(PHP v8.1.4)을 이용한 Restful API 샘플용  
composer create-project laravel/laravel SP_BO_LARAVEL_231215

# 실용

SP_BO_LARAVEL_RESTAPI_V1  
Laravel v10.37.3(PHP v8.1.4)을 이용한 Restful API 샘플용  
composer create-project laravel/laravel SP_BO_LARAVEL_RESTAPI_V1

# 사용한 artisan 명령어 정리

```bash
# 링크 폴더 설정
php artisan storage:link

# 모델 생성 & 마이그레이션 파일 생성
php artisan make:model Post -m

# 마이그레이션 프로세스 실행
php artisan migrate
```

# 커밋 메세지

1. API 리소스 생성

---

[Restful API] - API 리소스 생성

:원본파일생성

[Restful API] - API 리소스 수정

:소스변경

2. 모델 생성 & 마이그레이션

---

[Restful API] - 모델 & 마이그레이션 생성

:원본파일생성

[Restful API] - 모델 & 마이그레이션 수정

:소스변경

[Restful API] - 모델 & 마이그레이션 수정

:image필드 Eloquent Accessor 추가

3. 컨트롤러 생성

---

[Restful API] - 컨트롤러 생성

:원본파일생성

[Restful API] - 컨트롤러 수정 & API경로 추가

:소스변경
:API 경로 추가

4. 데이터베이스에 데이터 등록

---

[Restful API] - 데이터 등록

:등록 메소스(store) 추가
