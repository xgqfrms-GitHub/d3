# tutorial D3 

# [video](https://egghead.io/lessons/d3-get-started-with-d3?play=yes)

```js
var dataset = [ 5, 10, 15, 20, 25, 30, 35];

		d3.select('section').selectAll('div')
		  .data(dataset)
		  .enter()
		  .append('div')
		  .attr('class','bar')
		  .style('height',function(d){
		  	return d*7 + 'px';
		  });
```
```scss
section{
			padding-top: 50px;
			padding-left: 100px;
			border: 1px solid red;
			width: 300px;
		}
		.bar{
			display: inline-block;
			width: 20px;
			height: 75px;
			margin-right: 2px;
			background: teal;
		}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>D3 demo01</title>
	<style>
		section{
			padding-top: 50px;
			padding-left: 100px;
			border: 1px solid red;
			width: 300px;
		}
		.bar{
			display: inline-block;
			width: 20px;
			height: 75px;
			margin-right: 2px;
			background: teal;
		}
	</style>
</head>
<body>
	<div>
		<h1>D3 Data visualization 数据可视化</h1>
	</div>
	<section>
		<!--  -->
	</section>
	<!-- 
	<script src="https://d3js.org/d3.v4.min.js"></script>
	<script src="https://d3js.org/d3-selection.v1.js"></script>
	 -->
	<script src="../lib/d3/d3.v4.min.js"></script>
	<script src="../lib/d3/d3-selection.v1.js"></script>
	<script>
		var dataset = [ 5, 10, 15, 20, 25, 30, 35];

		d3.select('section').selectAll('div')
		  .data(dataset)
		  .enter()
		  .append('div')
		  .attr('class','bar')
		  .style('height',function(d){
		  	return d*7 + 'px';
		  });
	</script>
</body>
</html>
```
