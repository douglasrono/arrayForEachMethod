# arrayForEachMethod
The forEach() method calls a function (a callback function) once for each array element.
<p>Note that the function takes 3 arguments:</p>
<ul>
<li>The item value</li>
<li>The item index</li>
<li>The array itself</li>
<ul>
<p> The example above uses only the value parameter. The example can be rewritten to</p>
<code>
const numbers = [45, 4, 9, 16, 25];
let txt = "";
numbers.forEach(myFunction);

function myFunction(value) {
  txt += value + "<br>";
}
</code>
