一：let 与 const ,var 
var 声明的变量会提升，
const 声明时必须复制，声明后不能够修改，
let与const的区别：共同点：都具备块级作用域，都没有声明提前，不同点：变量的值可以变化，常量不可以，变量可以没有初始化，常量必须初始化。
二：promise:
  promise的状态不可逆，
  var p=new Promise(function(resolve,reject){
    resolve("success");
    reject("reject");
  });
  p.then(function(value){
    console.log(value);
  });
  p.catch(function(err){
     console.log(err);
  });
