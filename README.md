## 순서

- 다운받으면 pip install -r requirements.txt 실행 (virtualenv 다운되어있다는 전제)
- source bin/activate 실행 (실행 제거 = deactivate)
- python3 manage.py migrate
- 터미널에서 src 폴더에서 python(python3) manage.py runserver 사용시 8000포트에 연결

(더미파일 localhost:8000/warzone/ 에 있음 그냥 localhost:8000은 에러뜨는게 정상)
홍일이거 더미 페이지 확인 http://localhost:8000/tft/
