# pdfvuerprac
vue js에서 vue-pdf 사용 연습

vue-pdf 설치
1. vue create pdfvuerprac 으로 프로젝트 생성 (vue 버전은 2. 대 선택)
2. yarn 설치
  npm install -g yarn
  yarn --version
3. vue-pdf 설치
  npm install vue-pdf 또는
  yarn add vue-pdf
  (경험 상 yarn add vue-pdf가 더 잘 먹히는 듯 하다.)
4. 보여주고자 하는 pdf를 public 폴더 안에 위치할 경우
  <pdf src="/pdfvuerprac/sampleA.pdf"></pdf>로 pdf 파일을 출력할 수 있다.
  (단, 이 경우 pdf 파일의 첫 페이지만 출력된다. 모든 페이지를 순서대로 출력하기 위해선 v-for를 사용한다.)
