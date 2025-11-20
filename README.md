# NewsReader-Backend
NewsReader Backend source입니다. 새로운 기술을 적용하기 위한 레포입니다.

각 신문사의 RSS를 사용하기 때문에 영리적인 목적의 사용은 제제될 수 있습니다.

# CI/CD 규칙
## Commit
commit은 이름을 다음과 같은 명사로 시작해야 합니다.

[Feat] - 새로운 기능 추가        
[Fix] - 버그 수정                
[Refactor] - 코드 리팩토링            
[Docs] - 문서 수정               
[Style] - 코드 포맷팅 변경            
[Test] - 테스트 코드 추가 / 수정              
[Chore] - 프로젝트 구조 수정             

main 브랜치로의 직접적인 commit은 불가합니다.

## main 브랜치
실행가능한 코드가 존재하는 브랜치입니다.                 
직접적인 commit은 긴급한 수정외에는 허용하지 않습니다.

## release 브랜치
배포 브랜치입니다.                   
commit을 허용하지 않습니다.


## feat/ 브랜치
실 기능 개발 브랜치입니다.         


## PR
모든 PR은 feat/ --> main --> release로만 가능합니다.


# SPEC

## CI / CD

### github action workflow
1. auto-assigned bot             
2. pr-template bot                   
3. update CHANGELOG.md


## Backend Server

framework: Django            
package manager: uv

## RSS Server

