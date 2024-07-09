### 变量访问原则练习

1. ```javascript
   function f1() {
   	let num = 123
   	function f2() {
           
   		console.log( num )  
           
   	}
   	f2()
   }
   let num = 456
   f1() 
   ```
   
2. ```javascript
   function f1() {
   	let num = 123
   	function f2() {
   		let num = 0
   		console.log(num)
   	}
   	f2()
   }
   let num = 456
   f1()
   ```

3. ```javascript
   let a = 1
   function fn1() {
   	let a = 2
   	let b = '22'
   	fn2()
   	function fn2() {
   		let a = 3
   		fn3()
   		function fn3() {
   		let a = 4
   		console.log(a) //a的值 ? 
   		console.log(b) //b的值 ? 
   		}
   	}
   }
   fn1()
   ```

   

