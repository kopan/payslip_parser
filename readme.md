급여명세서 Parsing For 연말정산
=============

비밀번호는 무작위 대조로 맞추는 방식으로 입력이 필요 없습니다. 60~90년대생까지 처리 되어있습니다.  
chrome을 아래와 같이 실행해야 하는 이유는 iframe에 급여명세서를 띄우고 파싱하는데, 브라우저들이 local file을 iframe에 넣었을 시 접근이 안되도록 되어있기 때문입니다.  
내용을 다른곳에 저장하지도 않습니다.

### 1. 파일 준비
1. 하나의 디렉토리에 1~12월 급여 명세서 html 파일을 모아주세요.
2. 파일 이름은 1월 = 1.html ... 12월 = 12.html 이런 식으로 해주세요.
3. 이 프로젝트의 index.html 파일을 받아서 같은 폴더에 두세요.
### 2. Chrome 실행
1. Only!! Chrome에서만 동작합니다. chrome을 아래와 같이 실행하세요.
2. windows : 시작 -> 명령 프롬프트
```
"c:\Program Files (x86)\Google\Chrome\Application\chrome.exe" -allow-file-access-from-files
```
3. ubuntu, mac : 터미널에서 /path/to/chrome --allow-file-access-from-files
### 3. 2에서 실행된 chrome으로 1.3에서 받은 index.html을 실행시키면 끝. 
