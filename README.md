# manual-angularjs
for me


- ng-app :
- ng-model :
- ng-bind :

```html
<!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<body>

<p>Try to change the names.</p>

<div ng-app="myApp" ng-controller="myCtrl">

</div>

<script>

// AngularJS modules define applications:
var app = angular.module('myApp', []);

// AngularJS controllers control applications:
app.controller('myctrl', function($scope){

});

</script>

</body>
</html>
```
