# Hello Project 555 👋
프로젝트 555는 함께 무언가를 만들기 위한 개발자 3인으로 이루어져 있습니다.

# Plog
```java
public class Plog {
    private List<String> members;
    
    public Plog() {
        this.members = new ArrayList<>();
        this.members.add("Taeyoung Yang");
        this.members.add("Suyoung Yang");
        this.members.add("Sojin Shin");
    }
    
    public String sayAboutPlog() {
        String plog = "개발자들을 위한 블로그 서비스"
        
        while (workingHard(this.members)) {
            plog += goodQuality()
        }
        
        if (plog.isAwesome()) {
            return "Plog는 개발자들을 위한 블로그 서비스입니다."
        } else {
        return "DON'T LIE TO ME"
        }
    }
}
```

### [🏠 Plog가 궁금한가요?](https://project-555.github.io)

# Repository 구성
Project 555의 Repository 구성은 아래와 같이 이루어져 있습니다.

### [plog-back](https://github.com/project-555/plog-back)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
- Plog의 백엔드를 구성하는 소스 코드를 저장하고 있습니다.
- 배포 자동화 서비스 중지, 서비스 시작 등을 Github Actions를 간단히 수행할 수 있도록 되어있습니다.
- AWS ECS를 통해 배포되며, AWS RDS와 AWS ElasticCache를 통해 데이터베이스를 관리하는 형태로 구성되었습니다.

### [plog-front](https://github.com/project-555/plog-front)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- Plog의 프론트엔드를 구성하는 소스 코드를 저장하고 있습니다.
- React를 사용하여 구현되었으며, Material UI를 사용하여 구현되었습니다.
- AWS Amplify를 통해 배포되며, AWS S3를 통해 정적 파일을 관리하는 형태로 구성되었습니다.

### [plog-study](https://github.com/project-555/plog-study)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
- Plog의 개발에 필요한 기술조사를 진행하고, 팀원들과 공유하기 위한 저장소입니다.
- Plog의 프로젝트, 기술 도입 전 사전 조사를 하고 해당 내용을 팀원과 공유하기 위해 사용합니다.

### [project-555.github.io](https://github.com/project-555/project-555.github.io)
![Hugo](https://img.shields.io/badge/Hugo-black.svg?style=for-the-badge&logo=Hugo)![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
- Plog의 개발자들이 개발하면서 겪은 여정을 문서화하기 위한 저장소입니다.
- Hugo를 사용하여 정적 페이지를 생성하고, Github Pages를 통해 배포되는 형태로 구성되었습니다.
- Plog의 프론트, 백엔드 등 개발을 진행하면서 겪었던 내용, Plog를 구현하면서 세웠던 기준, 필요성 등에 대해 상세히 담고 있습니다.