# 트러플 환경 구축 및 배포한다. 함수 겟셋을 통해 샌드트랜잭션하기

- 1. test폴더를 만든다.
- 2. npm init -y 를 한다.
- 3. npm i truffle
- 4. npx truffle init
  - contracts : 솔리디티 파일을 생성해서 스마트 컨트랙트 코드를 작성하는 폴더
  - migrations : 배포 관련 코드 작성 폴더 (숫자*deploy*파일명.js ex: 1_deploy_test.js)
  - test : 테스트 코드 작성 폴더 (Jest를 사용한다.)
  - truffle-config.js => 트러플 설정 파일
- 5. contracts 폴더에 Test.sol을 생성 후 코드 작성.
- 6. 컴파일을하기 위한 명령어 npx truffle compile
- 7. 배포파일만들기 migrations에 파일 만든다.
- 8. 가나쉬 서버 열기
- 9. truffle-config.js에서 67번~71번 줄 주석 풀기.
- 10. npx truffle migration 으로 배포하기
- 11. 배포 후 CA(컨트랙트 어드래스) 가져온다. //0xBB2c1DD4e990eC2A32ed4eFEcA98acFBb1657418
- 12. npx truffle console 친다.
