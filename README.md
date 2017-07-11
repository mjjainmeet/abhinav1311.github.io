# abhinav1311.github.io


Welcome to github

<!doctype html>
<html ng-app>
  <head>
    <title>My AngularJS App</title>
    <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.5.6/angular.min.js"></script>
  </head>
  <body>
  <div ng-app >
  <b>Invoice:</b>
  <div>
    Quantity: <input type="number" min="0" ng-model="qty">
  </div>
  <div>
    Costs: <input type="number" min="0" ng-model="cost">
  </div>
  <div>
    <b>Total:</b> {{qty * cost | number:4}}
  </div>
</div>
  </body>
</html>
