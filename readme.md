'use strict';

function thousands_separators(num) {
  var i;
    if((parseInt(num)-num)==0){
      var str;
      i=num%3;
      var arr = new String(q);
      for(var j=0;j<i;j++){
          str+=parseInt(arr[j]);
      }
      str+=',';
      var count=0;
      for(var k=i;k<arr.length;k++){
          str+=parseInt(arr[k]);
          count++;
          if(count%3==0){
              str+=',';
          }
      }
      console.log(str);
  }
    else{
        var ary=new String(num);
        var stry;
        var number=parseInt(num);
        var l=number%3;
        var counte=0;
        for(k=0;k<l;k++){
            stry+=parseInt(ary[k]);
        }

        for(j=l;j<ary.length;j++){
            stry+=parseInt(ary[j]);
            counte++;
            if(counte%3==0){
                stry+=',';
            }
        }
        console.log(stry);
    }
}


module.exports = thousands_separators;
