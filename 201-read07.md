# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
>
>
# Here's some tips to follow when building your own domain models.

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.
# How to initialize properties in Javascript constructor
>Definition and Usage
- The constructor() method is a special method for creating and initializing objects created within a class.
- The constructor() method is called automatically when a class is initiated, and it has to have the exact name "constructor", in fact, if you do not have a constructor method, JavaScript will add an invisible and empty constructor method.
# Tables
## How to create tables
> Tables are defined with <table> tag and it is made of rows (<tr>) and columns (<td>). Tr means table row and td means table data.
_ To start creating table, you need an opening table tag, which is <table> and to end it, is to use table closing tag which is </table>.
_ To start creating horizontal table rows you need the opening tag <tr> and after entering number of column/s you need to end it with a closing tag </tr>.
_ To start making column in the table, as usual you need the opening tag <td> and after entering all the data, close it with a closing tag which is <td>.
_ To create another new column in a row, you can simply repeat the step described above before ending it with a tr closing tag, which is </tr>.
# ![](http://4.bp.blogspot.com/_9Jx2mcxSPVU/SyjT8MPtsJI/AAAAAAAABKA/tMHly2jTVxY/s400/How+to+create+tables+using+HTML+codes.jpg)
# Long Tables
> <thead>
* The headings of the table should sit inside the <thead> element.
<tbody>
* The body should sit inside the <tbody> element.
> <tfoot>
* The footer belongs inside the <tfoot> element. By default, browsers rarely treat
# Old Code: Width & Spacing
- here is a code examle:
<table width="400" cellpadding="10" cellspacing="5">
<tr>
<th width="150"></th>
<th>Withdrawn</th>
<th>Credit</th>
<th width="150">Balance</th>
</tr>
# Property accessors
## Property accessors provide access to an object's properties by using the dot notation or the bracket notation.
## Dot notation
- In the object.property syntax, the property must be a valid JavaScript identifier. (In the ECMAScript standard, the names of properties are technically "IdentifierNames", not "Identifiers", so reserved words can be used but are not recommended)
## Bracket notation
> In the object[property_name] syntax, the property_name is just a string or Symbol. So, it can be any string, including '1foo', '!bar!', or even ' ' (a space).
# ![ ](https://javascriptcode.org/wp-content/uploads/2020/04/bracket-notation-ie-results-1024x756.png)
## JavaScript adding decimal numbers issue [duplicate]
Definition and Usage
- Math.round()
- The round() method rounds a number to the nearest integer.
- 2.49 will be rounded down (2), and 2.5 will be rounded up (3).
# ![](https://www.w3resource.com/w3r_images/js-math-object-round.gif)



