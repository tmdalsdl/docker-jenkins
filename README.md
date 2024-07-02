# docker-jenkins
Dockerfile 생성 자동화
1. Hello world print 되는 파이썬 앱을 만들기
2. 해당 앱을 포함하는 폴더에서 git init 하고 **리모트 리포지토리**를 연결하기 
3. 젠킨스 프리스타일생성 
    1. 젠킨스가 **리모트 리포지토리** 를 폴링하게 합니다.
    2. 젠킨스가 Docker파일을 빌드하게 합니다.
    3. 빌드된 Docker 파일이 도커허브에 올라가게 합니다.
