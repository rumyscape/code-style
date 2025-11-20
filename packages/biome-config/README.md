# @bubbly-lab/biome-config

Bubbly Lab에서 사용하는 Biome 설정입니다.

## 사용법

- 기본 설정: `@bubbly-lab/biome-config/base.json`을 `extends`에 추가합니다.
- React/Tailwind 프로젝트: `@bubbly-lab/biome-config/react.json`을 `extends`에 추가합니다.

```json
{
  "extends": ["@bubbly-lab/biome-config/react.json"]
}
```

## 설정 파일 작성 팁

- 아래의 키 순서를 따르는 것을 컨벤션으로 합니다:

```
$schema
extends
vcs
files
assist
formatter
linter
{language specified rules - alphabetized order}
```
