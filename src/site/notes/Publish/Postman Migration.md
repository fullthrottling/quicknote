---
{"dg-publish":true,"permalink":"/Publish/Postman Migration/"}
---



# Tabbed Postman TO New 
# 문제 사항
## Tabbed Postman 지원 중단
>[!info] 크롬 플러그인 공식 지원 중단
>https://chromewebstore.google.com/detail/tabbed-postman-rest-clien/coohjcphdfgbiolnekdpbcijmhambjff?pli=1
>![Pasted image 20250327111350.png](/img/user/Publish/data/Pasted%20image%2020250327111350.png)

## 사용자별 케이스
### 신규 사용자
이용 불가
### 기존 설치자
앱 강제 사용 거부 이용 시 이용 불가

# 기왕 바꾼다면..
## 기존에 필요하다고 생각했던 기능들
1. 대상 서버를 좀 더 편하게 설정하여 배포
2. 배포가 좀 더 편했으면 ?
	1. 기존 시퀀스
		1. debug.json google drive download
		2. web postman import
		3. 작업 내용 추가
		4. export
		5. debug.json google drive upload\
	2. 배포 및 적용 단축
		1. Git 방식
			1. Git 통한 배포 공유
		2. Web Storage
			1. 보통은 유료 기능
				1. 유저에게 권한 제공 후 Api Collections WorkSpace Share 이후 실시간 반영
3. API 가이드 문서의 선택적 제공
	1. 사용법(인자 설명)
	2. 주의 사항

# 필요 작업
### 1. 마이그레이션 가이드 문서 갱신
 - 추가적으로 어떤 방향으로 선택 할지 결정 후 가이드 작성
### 2. 서버팀 Json Export 가이드

# 대안 프로그램 요약

| Name        | Official                                    | License                                                                                      | Down                                       | 가입필요 | 오프라인사용 | 장점              | 단점  |
| ----------- | ------------------------------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------ | ---- | ------ | --------------- | --- |
| **Postman** | [Site](https://www.postman.com/)            | [프리웨어](https://gytni.com/new_gytni/qna.php?document_srl=25138&mode=qna&mode2=view&mode3=chk) | [Down](https://www.postman.com/downloads/) | Y    | N      | [[Publish/Postman Migration#Postman-장점\|#Postman-장점]] | -   |
| **Bruno**   | [Github](https://github.com/usebruno/bruno) | [MIT License](https://namu.wiki/w/MIT%20%ED%97%88%EA%B0%80%EC%84%9C)                         | [Down](https://www.usebruno.com/)          | N    | Y      | -               | -   |
| **ApiDogs** | [Site](https://www.usebruno.com/)           | [프리웨어?](https://legal.apidog.com/terms-of-service-645649m0)                                  | [Down](https://apidog.com/download/)       | Y    | N      | -               | -   |
| OpenApi     | -                                           | -                                                                                            | -                                          | -    | -      | -               | -   |
|             |                                             |                                                                                              |                                            |      |        |                 |     |

# 대안 프로그램
## Postman
### Postman-장점
>[!info]+ 장점
>- 그룹내 보편적인 사용 프로그램
>	- 타조직, 부서에서 대중적인 사용
>		- 네오
>		- 빌링 개발
>		- N2
>		- 기타 다수 부서
>- 



### Postman 단점
-


### 적용 후 시나리오
-
