# @bubbly-lab/biome-config

Bubbly Lab에서 사용하는 Biome 설정입니다.

## 사용법

- 기본: `base` 설정을 `extends`에 추가합니다.

```json
{
  "extends": ["@bubbly-lab/biome-config/base"]
}
```

- React 프로젝트: `base`와 `react` 설정을 `extends`에 추가합니다.
```json
{
  "extends": ["@bubbly-lab/biome-config/base", "@bubbly-lab/biome-config/react"]
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
