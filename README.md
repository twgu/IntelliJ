# IntelliJ

### Licenses 확인

Help>Register..

### 설정

* 새 탭 마지막에 열기
    1. Settings>Editor>General>Editor Tabs
    2. Tab Order>`Open new tabs at the end` 체크

* 탭 최대 개수 조절
    1. Settings>Editor>General>Editor Tabs
    2. Closing Policy>`Tab limit` 설정

* MyBatis.xml
    1. Settings>Editor>Inspections
    2. SQL>`No data sources configured` 체크 해제
    3. SQL>`SQL dialect detection` 체크 해제

* Typo 끄기
    1. Settings>Editor>Inspections
    2. Proofreading>`Typo` 체크 해제

* Duplicated 끄기
    1. Settings>Editor>Inspections
    2. General>`Duplicated code fragment` 체크 해제

* Eslint 끄기
    1. Settings>Editor>Inspections
    2. JavaScript and TypeScript>Code quality tools>`Eslint` 체크 해제

### 설정 초기화

* 전역 설정
    1. IDE system 디렉토리 삭제
        - Windows : C:\Users\\AppData\Local\JetBrains\IntelliJIdea2020.3
        - MacOs : ~/Library/Caches/JetBrains/IntelliJIdea2020.3
        - Linux : ~/.cache/JetBrains/IntelliJIdea2020.3
    2. IDE setting 디렉토리 삭제
        - Windows : C:\Users\\AppData\Roaming\JetBrains\IntelliJIdea2020.3
        - MacOs : ~/Library/Application Support/JetBrains/IntelliJIdea2020.3
        - Linux : ~/.config/JetBrains/IntelliJIdea2020.3

* 프로젝트 설정
    1. 프로젝트 경로 .idea 폴더 삭제
