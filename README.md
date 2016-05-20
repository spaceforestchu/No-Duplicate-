# No-Duplicate-
function noDups(array){
  var i, result = [];
	
	for( i = 0; i < array.length; i++){
		if(result.indexOf(array[i]) === -1){
		  result.push(array[i]);
    }
  }
   	return result;
}
 noDups([1, 2, 2, 3, 4, 4, 5, 5, 5]);
