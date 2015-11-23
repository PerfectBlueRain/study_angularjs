# proj_angular_basic

#### angular프로젝트
- ng-app
- ng-controller
```javascript
<.... ng-controller="PhoneListController">
```
- CDN
```javascript
<script type="text/javascript" charset="utf-8" src="http://ajax.googleapis.com/ajax/libs/angularjs/1.0.2/angular.min.js"></script>

```
- ng-model
```javascript
ng-model="searchKeyword"
ng-model="orderProperty"
```

- ng-repeat
- filter / orderBy
```javascript
<li ng-repeat="phone in phones | filter:searchKeyword | orderBy:orderProperty">
   번호 : {{phone.no}}<br />
...
</li>
```

- AJAX : $http
   - http://programmingsummaries.tistory.com/115
   - Chrome에서 실행시 크로스 도매인 문제 : 크롬에서는 보안정책상 로컬파일 로딩시 AJAX를 불러오지 못한다
   - http://iolothebard.tistory.com/494 / CORS를 한 마디로 요약하면, "요청을 받은 웹서버가 허락하면 크로스도메인이라도 Ajax로 통신할 수 있다"라는 정책이다. 기술적으로는 크로스도메인에 위치한 웹서버가 응답에 적절한 Access-Control-Allow-류의 헤더를 보냄으로써 크로스도메인 Ajax를 허용
