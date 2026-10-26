# 내연기관 열효율 변수 탐구 시뮬레이터

## 실행
`engine_efficiency_lab.html` 파일을 웹 브라우저에서 열면 됩니다. 별도 설치나 인터넷 연결이 필요하지 않습니다.

## GitHub Pages로 공개하기
1. GitHub에서 새 저장소(repository)를 만듭니다.
2. `engine_efficiency_lab.html`을 업로드합니다.
3. 파일 이름을 `index.html`로 바꾸거나, 저장소에 `index.html`로 업로드합니다.
4. 저장소의 Settings → Pages → Build and deployment에서 Deploy from a branch를 선택하고 `main` / `/(root)`를 지정한 뒤 Save를 누릅니다.
5. 게시가 완료되면 `https://사용자이름.github.io/저장소이름/` 형태의 주소가 만들어집니다.

## 데이터 해석 주의
- Toyota의 공식 자료는 특정 Dynamic Force 엔진의 최대 열효율 40%(가솔린), 41%(하이브리드)를 공개합니다.
- Hyundai Motor Group의 CVVD 발표 자료는 성능 4% 향상, 연비 5% 개선, 배출가스 12% 저감을 제시합니다. 연비 개선율은 열효율 퍼센트포인트 증가와 같지 않습니다.
- Mazda SPCCI 및 Mercedes-Benz 48V MHEV 설명은 각 제조사 자료를 참조합니다.
- 슬라이더에 따른 효율 계산은 교육용으로 만든 단순화된 예시 모델이며, 제조사 실측 데이터에 맞춰 회귀 분석한 값이 아닙니다. 실측 결과로 인용하지 마세요.

## 공식 참고자료
- Hyundai Motor Group CVVD: https://www.hyundai.news/uk/articles/press-releases/hyundai-motor-group-unveils-worlds-first-cvvd-engine-technology.html
- Toyota Dynamic Force Engine: https://global.toyota/en/mobility/tnga/powertrain2018/engine/
- Mazda e-Skyactiv X / SPCCI: https://mazdamediapacks.com/en/technology/press-releases/e-skyactiv-x-engine-technology.html
- Mercedes-Benz 48V mild-hybrid: https://media.mbusa.com/news/the-new-mercedes-benz-c-class-2
