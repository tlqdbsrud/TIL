# 20230807 TIL

#### 🟣 1. Unity  Window

![image](https://github.com/tlqdbsrud/TIL/assets/141490250/40ef39ec-d14f-4e74-af9b-9e6fb4336014)


**Scence:** 게임의 전체 Scence을 시각적으로 확인할 수 있는 공간. 제작 중인 World를 표시하는 상호적인 View 장면, 캐릭터, 카메라, 광원, 게임 오브젝트의 모든 타입을 선택하고 배치하는데 사용

**Game View:** 카메라를 통해 렌더링된 뷰(실제 게임을 하는 사용자 뷰)

**Tool bar:** 필수적인 작업 기능 접근, Scence 뷰와 오브젝트 조작

- **중앙:** 재생, 일시 정지, 다음 프레임 스텝 컨트롤 버튼
- **우측:** Unity Cloud Service, Unity 계정 접근, 레이어 메뉴(게임 사용), 레이아웃 메뉴(에디터 커스텀, 지정된 내용 변경, 기본 Default 화면)

**Project:** 좌측은 폴더 계층 구조, 우측은 폴더 내 콘텐츠를 아이콘으로 보여줌.

**Hierachy(계층 구조):** 게임 오브젝트 리스트

- **Visibility Toggle:** 오브젝트를 보거나 숨기기 가능
  
**Inspector:** 선택된 오브젝트의 속성, 편집 가능  
    

    
#### 🟣 **2. Unity 프로젝트 폴더** 

**Assets**

- Unity에 사용하는 Assets에 포함되는 주 폴더
- Editor 프로젝트 창에 보이는 콘텐츠
- Editor 내에 접근 가능한 폴더
- 버전 관리 시스템에 필수적으로 업로드를 해야 하는 폴더
- Unity 프로젝트에 실제로 사용하는 파일들이 저장되는 Assets 폴더는 삭제하여서는 안 됨.

**Library**

- Assets을 런타임에 사용하기 위해, 내부적으로 읽을 수 있도록 자체 포맷으로 변환한 것을 저장하는 파일
- Assets 폴더와 ProjectSettings 폴더를 (re)import할 때 생성
- 임의로 수정하면 안 됨. 📌
- 폴더 자체 삭제를 해도 상관 없음.(Unity 작동 중 삭제 안 됨)
- 자동 생성

**Packges**

- Unity Packges 파일의 정보들을 저장
- json형태의 파일 존재
- Unity에 존재하는 여러 패키지 개념 존재
- 프로젝트 공유 시, 동일한 환경을 만들 때 꼭 필요하므로 패키지 정보 삭제하면 안 됨.

**ProjectSetting** 

- asset과 text 파일 존재, Unity 정보 기록
- 에디터의 Edit > Project Settings 등에서 설정된 설정 값들을 저장
- `ProjectSetting.asset` : 가장 많이 수정하게 될 setting
