# Laravel Jetstream 메세지 한글화

1. 다운 받은 /resources/lang/ko.json 화일을 resources/lang 안에 넣어 주고,
2. /resources/lang/ko/validation.php 안에 아래 코드를 추가해 줍니다.

```
    'attributes' => [
        'name' => '이름',
        'email' => '이메일',
        'password' => '비밀번호',
    ],
```
