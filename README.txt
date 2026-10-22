Ascetic Type Lab — 배포용 폴더

이 폴더 전체를 그대로 정적 호스팅에 올리면 됩니다. (서버 코드 필요 없음)

[가장 쉬운 방법] Netlify Drop
1. https://app.netlify.com/drop 접속 (무료 가입)
2. ascetic-type-lab 폴더를 화면에 끌어다 놓기
3. 바로 주소가 생깁니다. Site settings에서 주소 이름을 바꿀 수 있어요.

[GitHub Pages]
1. GitHub에 새 저장소를 만들고 이 폴더 안의 파일을 모두 올리기
2. Settings → Pages → Branch: main / (root) → Save
3. 1~2분 뒤 https://<아이디>.github.io/<저장소이름>/ 으로 열립니다.

주의
- index.html을 파일로 더블클릭해서 열면 폰트·데이터가 안 불러와집니다. 반드시 호스팅(또는 로컬 서버)으로 열어 주세요.
- 3D 히든 페이지는 three.js를 cdnjs에서 불러오므로 인터넷 연결이 필요합니다.
- OTF 다운로드 버튼은 otf 폴더의 파일을 zip으로 묶어 바로 내려받게 합니다.

Direct & Design by Jaeyun Choi
