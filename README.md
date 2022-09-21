# React JS에서 완전히 반응하는 최신 UI/UX 웹 사이트 구축 및 배포

Youtube [Create React App](https://www.youtube.com/watch?v=LMagNcngvcU).

## Deployment(배포)

### `FTP 사용`

터미널 : npm run build -> build 폴더 생성 : \
FTP 접속후 public 또는 html 폴더 안에 내 컴퓨터에 생성된 build 폴더 안에 파일을 넣는다.

### `github 사용`

터미널 : npm i gh-pages (gh-pages는 github의 github page 도메인을 만들어준다.) \   
package.json 안에 \        
  "scripts": {\
    "deploy": "gh-pages -d build",\
    "predeploy": "npm run build"\
  },\  
  맨 마지막에 홈페이지 주소 입력\
  "homepage": "https://keegi.github.io/gpt3/"\
  }\
  이후 터미널에 npm run deploy 실행  ->  github 도메인 https://keegi.github.io/gpt3/ 실행됨.

## 추가 설치 파일

npm install react-icons

### `참고사이트`

온라인 Gradient Generator = 'https://angrytools.com/gradient/' \
애니메이션 코드 생성 = 'https://animista.net/play/basic' \
BEM 가이드 = 'https://sparkbox.com/foundry/bem_by_example'

GitHub Code (give it a star ⭐) - https://github.com/adrianhajdin/project_modern_ui_ux_gpt3 \
Assets - https://minhaskamal.github.io/DownGit/#/home?url=https:%2F%2Fgithub.com%2Fadrianhajdin%2Fproject_modern_ui_ux_gpt3%2Ftree%2Fmain%2Fsrc%2Fassets \
Styles - https://gist.github.com/adrianhajdin/f944d6e74d2ce1922efebe55c908d0d8 \
Figma Design - https://www.figma.com/file/lz9lLpFHMxHm2odnwM3R0z/gpt3?node-id=0%3A1 \
AR Shakir's Designs - https://www.arshakir.com/

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

