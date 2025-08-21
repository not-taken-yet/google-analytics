# 웹 데이터 스트림 생성
- 데이터 스트림 생성 화면에서 웹을 선택하고 웹사이트 URL 이벽
- 웹사이트 전용 **측정 ID**와 태그가 발급됨
- 만약 웹사이트 빌더나 CMS를 사용한다면, 해당 측정 ID를 복사해서 웹사이트 빌더 계정 설정에 붙여넣으면 됨

<hr>

# 웹사이트 태그 설치 방식

## Google Tag Manager 사용 (추천)
 
- 사이트 코드에 직접 붙여넣지 않고, 계정 인터페이스에서 태그를 관리할 수 있게 해줌
- 여러 마케팅 태그나 웹사이트 태그를 한 곳에서 관리하고 업데이트할 수 있음
- CMS나 웹사이트 빌더를 쓰는 경우에도 Tag Manager로 연결할 수 있음

## 수동 설치 (직접 코드 넣기)

- Analytics에서 발급해준 웹 태그 코드를 직접 복사해서 모든 웹페이지의 `<head>` 태그 바로 뒤에 붙여넣기
- Once added, this establishes the connection between your website and your new Analytics property and starts collecting data.

<hr>

# In the end

- <mark>Use Google Tag Manager to deploy the tag</mark>
- <mark>Manually add the tag to the website code</mark>
- <mark>Provide your tag or measurement ID to a website builder</mark>
	- For some website builders, all you need to do is copy the measurement ID and paste it in your account.
	- Other website builders require more work to add the code.
