# Angular.js

## Web Application 개발도구
- Yeoman설치 : yo / bower / grunt 명령
- node.js 설치 : npm 명령 (개발 및 grunt 라이브러리 관리)
- Git 설치 : git 명령


### Yeomen
- Yo : 자동생성 도구
- bower : js의존성 라이브러리 관리, 프런트엔드 의존성 아이브러리를 원격으로부터 내려받고 index.html에 자동으로 설정
- grunt : js애플리케이션 빌드 도구, 프런트엔드의 테스트/통합/압축 등 빌드 배포작업

```
$ npm install -g yo
$ npm install -g bower
$ npm install -g grunt-cli
```

### 프로젝트 생성

```
$ npm install -g generator-angular
$ yo angular <project name>
$ bower install // bower.json, bower_components
$ npm install // package.json, node_modules

$ grunt serve  // Gruntfile.js
$ grunt test   // test/spec 폴더에 작성된 단위테스트 코드
$ grunt build  // dist폴더에 배포버전
```
