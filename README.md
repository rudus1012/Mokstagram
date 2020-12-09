# Mokstagram

학생들의 편의를 위해 ReactJS와 Django를 사용하여 Instagram을 모티브로 한 사진 기반의 교내 SNS를 제작 합니다. 제작하는 서비스는 간단한 회원가입과 Facebook을 연동한 로그인 서비스를 지원하며, 사진 기반의 SNS인 만큼 피드에 사진을 추가하여 회원들 간 소통할 수단으로 사용합니다. 또한 사진에 댓글과 좋아요 기능을 지원해 SNS의 기능을 완성합니다. 제 안하는 서비스를 통해 불편했던 소통의 장을 만들어 교내 커뮤니티를 활성화 할 수 있는 SNS를 제공합니다.

# 시스템 구성도

<img width="1181" alt="sns구성도" src="https://user-images.githubusercontent.com/43171179/101591117-18454980-3a2f-11eb-94b3-fbbb4e34c0f4.png">

* 인터페이스 구축을 위하여 자바스크립트 라이브러리인 ReactJS를 사용하였으며 웹사이트를 개발하기 위하여 파이 썬으로 작성된 오픈 소스 웹 애플리케이션 프레임워크 Django를 사용하였습니다. 
* ReactJS를 사용하여 FrontEnd(User Interface,UI)를 구성하고 간편 회원가입과 로그인, Facebook login API를 연동해 Facebook 기존 회원 ID와 Password로 로그인도 가능하다.
* Django를 사용하여 메인 피드 구성, 좋아요 및 댓글 기능 등 BackEnd를 커스터마 이징한다. 
* 데이터베이스 정보를 PostgreSQL을 통해 관리 하고, 확장 기능들은 AWS를 사용하여 관리한다. 
* 안정성을 위해 NAS를 통해 데이터를 백업 한다.
