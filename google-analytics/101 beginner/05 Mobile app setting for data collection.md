- **앱 데이터 스트림**은 Firebase SDK로 구동됨 
- <mark>앱이 이미 Firebase를 사용 중이라면, Firebase 콘솔에서 Analytics를 활성화할 수 있음</mark>
- <mark>앱이 Firebase를 사용하지 않는다면, Google Analytics가 새 Firebase 프로젝트를 만들어준다</mark>

**설정 단계**:
1. 관리자(Admin) → 데이터 스트림(Data Streams)으로 이동
2. 새 데이터 스트림 추가 → 앱 플랫폼(iOS / Android) 선택
	- <u>두 플랫폼에 모두 있다면 각각 따로 스트림을 만들어야 함</u>
3. Android는 **패키지명**, iOS는 **번들 ID** 필요
4. 앱 정보 입력 후 Next 클릭
5. GA가 Firebase 프로젝트를 만들고 앱 데이터 스트림을 설정해줌

**필수 조건**
- 앱에서 사용자 활동을 측정하려면 **Firebase SDK를 구현**해야 함
- Firebase가 연결되면 몇 가지 이벤트는 자동 수집된 (예: 앱 첫 실행, 인앱 결제, 화면 조회)
- 그 외에 비즈니스에 필요한 **추천 이벤트**나 **커스텀 이벤트**를 추가로 수집 가능

<hr>

# In the end

```
앱 데이터 스트림 생성 → Firebase 프로젝트 연결 → SDK 구현 → 자동 이벤트 수집 + 커스텀 이벤트 추가 → GA에서 통합 분석.
```

비즈니스와 관련된 **추천 이벤트**를 추가로 수집할 수 있음

> **logEvent 메서드**를 사용해 최대 500개의 이벤트 이름을 정의하고 수집할 수 있으며, 총 이벤트 수집량에는 제한이 없음

<mark>앱 데이터를 GA로 보내기 위해서는 Firebase SDK를 써야 함</mark>