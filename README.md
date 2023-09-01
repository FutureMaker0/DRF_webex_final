# DeveLearn
  - 팀명: DeveLorm
  - 주제(서비스명): 온라인 학습 플랫폼
    - 클래스를 운영하는 선생님과, 원하는 클래스를 수강하는 학생 간의 교육이 이루어지는 온라인 학습 플랫폼입니다.
  - REPO 주소: https://github.com/DevelOrm/DeveLearn

  ![메인](https://github.com/FutureMaker0/DRF_webex_final/assets/120623320/c04c8f3f-feac-48d2-9e5e-6036a6ca66e0)

# 개발 기간
  - 23.8.17 ~ 23.09.04

# DataBase Structure
  -

# API 명세
  - http://3.37.187.68:8000/api/swagger
  - http://3.37.187.68:8000/api/redoc
  - 테스트 계정 (authenticated 된 계정만 접근할 수 있습니다.)
      - id: test
      - pw: testpw00

# 배포 서버 구조
  <img width="1796" alt="서버구조" src="https://github.com/FutureMaker0/DRF_webex_final/assets/120623320/c233f21d-3ed8-4107-aec1-1a064fafdee8">

# Index
  1. 기술스택 & 개발환경
  2. 팀원소개 및 역할
  3. 프로젝트 요약
  4. 주요 기능 소개
  5. 라이브 데모
  6. 개발 중 장애물 & 극복 방법
  7. 추가 및 리서치 하고 싶은 기능
  8. 프로젝트 소감 (어려웠던 점 & 배운점 & 향후 계획)
  9. Q & A

# 1. 기술 스택 & 개발 환경
<table>
    <thead align="center">
        <tr>
            <th><span>BE</span></th>
            <th><span>FE</span></th>
            <th><span>DB</span></th>
            <th><span>DESIGN</span></th>
            <th><span>DEPLOYMENT</span></th>
            <th><span></span>MANAGEMENT</th>
        </tr>
    </thead>
    <tbody>
          <td align="center">
              <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
              <img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white">
          </td>
          <td align="center">
              <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
              <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
              <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
          </td>
          <td align="center">
              <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white">
          </td>
          <td align="center">
              <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
          </td>
          <td align="center">
              <img src="https://img.shields.io/badge/amazon LightSail-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
              <img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
              <img src="https://img.shields.io/badge/amazon RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white">
              <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
              <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white">
          </td>
          <td align="center">
            <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
            <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
            <img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
          </td>
    </tbody>
</table>
     
# 2. 팀원소개 및 역할
<table>
    <colgroup>
        <col style="width: 200px;">
        <col style="width: 200px;">
        <col style="width: 200px;">
        <col style="width: 200px;">
        <col style="width: 200px;">
    </colgroup>
    <thead align="center">
        <tr>
            <th>★남궁범★</th>
            <th>이지섭</th>
            <th>주기현</th>
            <th>김재현</th>
            <th>박종수</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">
                <img width="125px" src="https://avatars.githubusercontent.com/u/90359639?v=4"/>
            </td>
            <td align="center">
                <img width="125px" src="https://avatars.githubusercontent.com/u/89283288?v=4"/>
            </td>
            <td align="center">
                <img width="125px" src="https://avatars.githubusercontent.com/u/95518318?v=4"/>
            </td>
            <td align="center">
                <img width="125px" src="https://avatars.githubusercontent.com/u/120623320?v=4"/>
            </td>
            <td align="center">
                <img width="125px" src="https://avatars.githubusercontent.com/u/131739329?v=4"/>
            </td>
        </tr>
        <tr>
            <td align="center">
                <a href="https://github.com/tombeom">@tombeom</a>
            </td>
            <td align="center">
                <a href="https://github.com/vBORIv">@vBORIv</a>
            </td>
            <td align="center">
                <a href="https://github.com/rlguswn">@rlguswn</a>
            </td>
            <td align="center">
                <a href="https://github.com/FutureMaker0">@FutureMaker0</a>
            </td>
            <td align="center">
                <a href="https://github.com/jongsoo-P">@jongsoo-P</a>
            </td>
        </tr>
        <tr>
            <td align="center">유저, 인증 관련 개발</td>
            <td align="center">뉴스 CRUD 구현</td>
            <td align="center">게시판 CRUD 구현</td>
            <td align="center">코드 리팩토링, drf-spectacular</td>
            <td align="center">s3 버킷 파일 업로드, Nginx 배포</td>
        </tr>
    </tbody>
</table>


# 3. 프로젝트 요약
  - 서비스 전체 개요
    - 온라인 학습 플랫폼 DeveLearn은 선생님-학생 간 학습이 이루어지는 공간입니다.
    - 선생님은 기술스택 별 클래스를 개설하고 문제출제(문제게시판), 강의자료 게시(자료게시판), 질문대응(질문게시판)을 수행합니다.
    - 학생은 원하는 기술스택 클래스를 수강하며 문제 답변제출(문제게시판), 강의자료 다운로드(자료게시판), 질문등록(질문게시판)을 할 수 있습니다.
    - 선생님이 출제하고 학생이 제출한 문제 답변을 자동으로 채점하여 결과를 피드백합니다.
    - 사용자별(학생, 선생님) 클래스 구독 정보를 알 수 있습니다.
    - IT업계 동향을 파악할 수 있는 최신 뉴스를 홈페이지에서 보여줍니다.
      
  - 서비스 개발 관점
    - drf-spectacular를 적용해 API 명세를 작성하여 협업 간 효율증진을 도모하였습니다.
    - 서비스를 실 배포하여(Lightsail, EC2활용) 추후 운영이 가능하도록 하였습니다.
   
  - 협업
    - Notion 기반 프로젝트 일정관리 진행하였습니다.
    - 협업 효율 최적화를 위해 일 3회(9/13/16시) 정기회의를 진행하였습니다.

   
# 4. 주요 기능 소개
  - Classroom
    > 클래스룸 - 게시판 - 댓글 구조의 기본 CRUD 기능을 제공한다
    
    - 클래스룸
    게시판의 종류는 문제 게시판, 강의자료 게시판, 질문 게시판 총 3가지가 있다
    선생님으로 지정된 유저가 클래스룸, 게시판을 생성할 수 있고 클래스룸을 구독한 유저들이 이를 자유롭게 이용 가능하다
    - 문제 게시판
    선생님으로 지정된 유저가 문제 게시글을 생성하면 각 유저들이 자유롭게 문제에 대한 댓글 혹은 답변 제출이 가능하다
    auto_score가 true인 문제 게시글에 유저가 답변을 제출하면 미리 지정된 문제 게시글의 solution필드와 비교해 채점하며 정답 여부가 answer_status필드에 저장된다
    
    ```python
    ## models.py
    class Test(models.Model):
        solution = ArrayField(models.CharField(max_length=50, blank=True), null=True, blank=True)
        auto_score = models.BooleanField()
        # ...
    
    ## views.py TestSubmitView
    def post(self, request):
        try:
            test_pk = request.data['test']
            test_obj = Test.objects.get(pk=test_pk)
            if request.user.is_authenticated:
                solution = test_obj.solution
                user_answer = request.data['user_answer']
                if test_obj.auto_score:
                    answer_status = user_answer in solution
                else:
                    answer_status = None
        # ...
    ```
    
    - 강의자료 게시판
    선생님으로 지정된 유저가 학습용 파일, 이미지, 텍스트를 게시글로 작성할 수 있고 유저들이 자유롭게 이용 가능하다
    - 질문 게시판
    클래스룸을 구독한 유저 모두가 이용 가능하며 이미지를 첨부해 게시글을 작성할 수 있다
    - 댓글
    로그인된 유저는 각 게시판의 게시글에 댓글을 작성할 수 있다
    
  - News
    
    
  - User

  

# 5. 기능(APP)별 라이브 데모
| APP | 이미지/데모 | 비고 |
|---|:--------:|:---:|
| Classroom | <img width="1468" alt="클래스룸 목록" src="https://github.com/FutureMaker0/DRF_webex_final/assets/120623320/730c9291-4f3a-4aac-aac1-251f939a84e1"> | 클래스룸 목록 |
| Classroom | <img width="1470" alt="클래스룸 상세" src="https://github.com/FutureMaker0/DRF_webex_final/assets/120623320/9907d955-ac78-4181-a13d-fe66f6107e41"> | 클래스룸 상세 |
| News | <img width="1469" alt="뉴스 목록" src="https://github.com/FutureMaker0/DRF_webex_final/assets/120623320/bba85e7c-ee9b-49b7-bbda-bf2b749e8df6"> | 뉴스 크롤링 |
| User | <img width="1470" alt="로그인" src="https://github.com/FutureMaker0/DRF_webex_final/assets/120623320/641c4cc0-a4c2-4418-b181-b99a447ea33f"> | 유저 로그인 |
| drf-spectacular |<img width="731" alt="swagger" src="https://github.com/FutureMaker0/DRF_webex_final/assets/120623320/9ebc11a4-e655-4062-9bae-a2d240e4d2ce">| SWAGGER-UI |
| drf-spectacular |<img width="854" alt="redoc" src="https://github.com/FutureMaker0/DRF_webex_final/assets/120623320/71ad9542-cd88-4852-975c-14b8b2c38fda">| REDOC-UI |


# 6. 개발 중 장애물 & 극복 방법
  <table>
    <thead align="center">
        <tr>
            <th><span>기능(APP)</span></th>
            <th><span>장애물</span></th>
            <th><span>극복방법</span></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center" rowspan="2">
                <a>Classroom</a>
            </td>
            <td align="center">
                <a>이미지 필드와 파일 필드의 업로드 문제</a>
            </td>
            <td align="center">
                <a>> JSON raw 데이터로만 CRUD기능을 테스트하던 중, 이미지와 파일이 포함된 POST 요청을 보내는 방법을 숙지하지 못함 요청하는 데이터의 body를 raw 데이터가 아닌 form-data형식으로 요청하여 해결</a>
            </td>
        </tr>
        <tr>
            <td align="center">
                <a>업데이트뷰 작성시 부분 업데이트 에러 문제</a>
            </td>
            <td align="center">
                <a>> serializer의 'partial=True' 옵션을 사용해 유효성 검사를 완화하여 검사에 실패한 필드가 있더라도 업데이트가 가능하도록 함</a>
            </td>
        </tr>
        <tr>
            <td align="center" rowspan="3">
                <a>drf-spectacular</a>
            </td>
            <td align="center">
                <a>지금까지의 프로젝트에서 활용해본 적이 없는 새로운 개념으로 배경지식 부족</a>
            </td>
            <td align="center" rowspan="2">
                <a>> 공식문서 활용 및 관련 내용을 다룬 기술 블로그 참조</a>
            </td>
        </tr>
        <tr>
            <td align="center">
                <a>활용법 미숙지로 인해 setting 및 적용하는 과정에서 장애 발생</a>
            </td>
        </tr>
        <tr>
            <td align="center">
                <a>spectacular ui 적용 후, 단순 적용에서 나아가 view layer수준 api doc 커스터마이징 과정에서 장애 발생</a>
            </td>
            <td align="center">
                <a>> 전체 서비스 내 app별로 view 상속 레벨이 다른 경우, drf-spectacular가 매번 같은 형태로 적용하지 않으며 다른 방식을 취함을 스터디 후 적용</a><br>
                <a>> @extend_schema / @extend_schema_view / @extned_schema_serializer 등이 있고 동시 적용 시 우선순위가 존재</a>
            </td>
        </tr>
    </tbody>
</table>


# 7. 추가 및 리서치 하고 싶은 기능
  - Classroom
    - 게시글에 영상을 첨부해 재생할 수 있는 기능
    - 신고 기능(분탕 유저 신고 기능, 오타수정 제보 기능, 에러 제보 기능 등))
   
  - News

  - User

  - drf-spectacular
    - View 클래스 내부 메소드 단위의 schema를 일괄적으로 적용한 것에 대한 아쉬움 존재
    - 단순 적용 및 담당 serializer를 request/response하여 api 동작을 확인하는 것에 추가로, 메소드별 커스터마이징 추가적용 희망
      - 커스터마이징 시 각 파라미터별 역할과 사용법을 좀 더 익혀 서비스 개발 시 협업에 큰 도움이 되는 drf-spectacular에 대한 이해도와 활용 스킬을 증진하고자 함


# 8. 프로젝트 소감 (어려웠던 점 & 배운점 & 향후 계획)
  - 어려웠던 점 (trouble shooting)
  - 배운점
  - 향후 계획
