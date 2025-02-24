빌드 후 EC2 에 배포.
Linux/UNIX (Ubuntu24.04)

ssh 접속을 위한 RSA(.pem) 키 생성 후 외부 툴(mobaxterm)을 통해 EC2 인스턴스에 접속.

scp 명령어를 통해 local 에서 EC2 인스턴스로 빌드 파일 전송.

EC2에 자바 설치 후 해당 파일 실행 -> 외부에서 80포트로 접근 확인.
