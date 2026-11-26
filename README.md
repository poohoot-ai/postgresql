# Postgre 연습

#### 백그라운드 실행
```console
docker compose up -d
```

#### VS Code / 외부 클라이언트 접속
- Host: localhost
- Username / Password: .env에 설정한 값
- Port: 5433

#### 완전 삭제 및 데이터까지 초기화
```console
docker compose down -v
```