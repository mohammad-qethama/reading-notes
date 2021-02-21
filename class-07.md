# Class-07

## Domain Modeling

>Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.
>Here's some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the `new` keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the `this` variable within methods so you can access the object's properties and methods from inside.

>https://github.com/codefellows/domain_modeling#domain-modeling; quoted on 21/2/2021.

## Tables 'HTML'

Tables are used to display alot of data type , as HTML descripes the page content elements and their structure it can mark up elements as tables and the will be rendered as one in the browsers.

```HTML
<table>
  <tr>
    <td>15</td>
    <td>22</td>
    <td>32</td>
  </tr>
  <tr>
    <td>17</td>
    <td>23</td>
    <td>42</td>
  </tr>
</table>
```

* `<table>` element markup all the contant of the table.

* tables filled row by row so the `<tr>`(table row) tag used to declare the beginning of new row.

* `<td>`(table data) is the data tag been filled in the rows cell by cell.

* Table heading can be added using `<th></th>` and the are used like `<td>` tags.

* long table can uses extra tags to orgnizing them so the are featured in HTML and they are:

```HTML
 <table>
  <thead>
    <!-- place all the header rows and data  i.e titles  here -->
  </thead>
  <tbody> 
    <!-- all data rows placed here -->
  </tbody>
  <tfoot>
    <!-- the outro data/conclusion/summation rows added here     -->
  </tfoot>
</table>
```

* you can increase cell span using attr `rowspan=''` and `colspan=''` to increase each cell span.

* books mentioned other old atrr that was replaced by CSS styling.

***

## Objects

* there is away to update  objects called **constructor syntax**

```JS
let pcMasterRace = new object(); 
pcMasterRace.videoCard = 'RTX 3090'; 
pcMasterRace.isExpensive = true  ; 
pcMasterRace.cpu = 'ryzen threaddripper'; 
pcMasterRace.tempruter = function(){
  if (temp> 50){
      startFans();
  }else {
      stopFans();
  }

}
```

* you can use `delete obj.property` to delete a property from objects.

* the lines like `pcMasterRace.isExpensive = true;` used to add or to edit properties in  objects.

* global scope is the top level of the code.

* If a named function has been defined in global scope, and it is then used as a method of an object.

* `function()` used to construct multiple array's.

```js

function city(people, buldings){

    this.people = people;
    this buildings = buildings; 
   
}

var city1 = new city('1000','50 building');
var city2 = new city('9000','1500 building');

```

* both `city1`and `city2` are objects with same keys and different values.

* arrays are objects with fixed keys called indices
