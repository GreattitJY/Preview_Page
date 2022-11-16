# Preview_Page

Preview_Page

# 커밋 컨벤션

HTML : 마크업을 수정한 경우  
Feat : 새로운 기능을 추가할 경우  
Fix : 버그를 고친 경우  
Design : CSS 등 사용자 UI 디자인 변경  
!HOTFIX : 급하게 치명적인 버그를 고쳐야하는 경우  
Style : 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우  
Refactor : 프로덕션 코드 리팩토링  
Comment : 필요한 주석 추가 및 변경  
Docs : 문서를 수정한 경우  
Test : 테스트 추가, 테스트 리팩토링(프로덕션 코드 변경 X)  
Chore : 빌드 태스트 업데이트, 패키지 매니저를 설정하는 경우(프로덕션 코드 변경 X)  
Rename : 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우  
Remove : 파일을 삭제하는 작업만 수행한 경우

# 코드 컨벤션

- html, css, js 클래스명 규칙

  - html, css는 하이폰, js는 카멜케이스, 노드는 $

- btn btn-color
- 형태-의미

# 브라우저 지원 대상

- IE 제외

# 💥 issue

## ❗️ li 내 요소를 스크린리더가 읽지 않는 문제 발견

- Solution : tabindex를 사용하여 스크린리더가 tab을 인식하도록 설정하였습니다.
- 주의사항 : tabindex를 0보다 큰 값을 줄 경우 논리적 순서가 바뀜으로 항상 0으로 사용해야 합니다.
- [tabindex MDN 공식문서](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex)

- [tabindex caniuse](https://caniuse.com/?search=tabindex)

- [ARIA:list role MDN 공식문서](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/list_role)
