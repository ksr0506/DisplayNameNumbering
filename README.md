# DisplayNameNumbering

Workflow내에 사용된 Activity의 DisplayName을 중복되지 않게 번호를 달아주는 Library입니다.


Studio & Package Version
---

해당 라이브러리는 아래의 패키지 버전 및 스튜디오 사양으로 개발했습니다.

- Studio Version
  - UiPath Studio (2021.10.4)

- Package Version
  - UiPath.System.Activities (min version 20.10.4)
  - UiPath.UIAutomation.Activities (min version 20.10.8)

Properties
---
Input
- FolderPath (String) 
  - 작업을 수행할 프로젝트 폴더 경로 (해당 값이 비어 있으면 folderBrowserDialog가 호출되어 경로 선택이 가능합니다.)
- Overwrite (Boolean) 
  - 복사할 폴더로 미리 생성된 백업폴더가 존재하면 덮어씁니다. (False로 설정 후 이미 폴더가 경로에 존재하면 에러가 발생합니다.)
