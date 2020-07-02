simple node example
1. create NodeJS folder
2. create node-examples sub folder open in cmd
3. npm init
4.{

    "name": "node-examples",

  "version": "1.0.0",

  "description": "Simple Node Examples",

  "main": "index.js",

  "scripts": {

    "test": "echo \"Error: no test specified\" && exit 1",

    "start": "node index"

  },

  "author": "Dhanush",

  "license": "ISC"

}
5. create file index.js write js code
	var rect={
		per and area}
	function solverect(l,b){
		console.log(rect.area(l,b))
		console.log(rect.perimetre(l,b))
	}
	solveRect(2,4)



//simple node example
6. create recatncgle.js file
	exports.area and perimeter

7. in step 5 code in var react=require('./rectangle')

// simple node module

8.
clear reactangle.js
	module.exports = (x,y,callback) => {
	if(x <= 0 || y<=0)
	{
		setTimeout(()=>callback(new Error("statement")//or null,null//or return value),2000//time in ms)
	}
	else
	{
		setTimerout(()=>callback(null,{
                	perimeter: () => (2 * (x + y)),
                	area: () => (x * y)
            		}),2000)
	}
	}
 9. change index.js to in solveRect(l,b)

	rect(l,b, (err, rectangle) => {
        if(err) {
            console.log("ERROR: ", err.message);
        }
        else {
            console.log("The area of the rectangle of dimensions l = "
            + l + " and b = " + b + " is " + rectangle.area());
        console.log("The perimeter of the rectangle of dimensions l = "
            + l + " and b = " + b + " is " + rectangle.perimeter());
        }
   })
	
