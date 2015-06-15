var nameSpace = angular.module("ShopApp",[]);

nameSpace.controller("ShopFunction", ['$scope','$http', function($scope, $http)
		{    
			$http.get('js/data.json').success (function(data){
				$scope.shopVariable = data;
				$scope.orderShop = 'name';
			});
 
		}]
);