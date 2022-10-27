## 설치 가이드 영상
### `https://youtu.be/o7FkmtqIYOE`

## 스키마 업데이트
### `amplify push`

## API 임포트
### `import { API } from 'aws-amplify';`

## 데이터 추가 쿼리
### `API.graphql({ query: create~, variables: { input: { ~ } } })`

## 데이터 리스트 필터링 쿼리
### `API.graphql({ query: list~, variables: { filter: { author: { eq: ~ } } } })`
