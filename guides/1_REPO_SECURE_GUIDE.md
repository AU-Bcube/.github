# 리포지토리 생성 후 보안 가이드

## 기본 브랜치 Ruleset 설정

[MAIN_BRANCH_MR_PR_RULESET.json](assets/MAIN_BRANCH_MR_PR_RULESET.json)을 사용하여 GitHub 리포지토리 Ruleset을 설정한다.

1. 리포지토리의 **Settings > Rules > Rulesets**로 이동한다.
2. **New ruleset > Import a ruleset**을 선택하고 위 JSON 파일을 업로드한다.
3. 내용을 확인한 뒤 **Create**를 눌러 저장한다.

## Security and quality 옵션 설정

리포지토리의 **Settings > Security and quality**에서 **Code quality findings**를 제외한 모든 옵션을 켠다.
