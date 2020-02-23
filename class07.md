# ** HTML & CSS / Chapter 6: “Tables” ** 

### A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.
### basic table structure:
### <table>
### <tr>  
### <td>
### long tables: There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content).
### <thead> :The headings of the table should sit inside the <thead> element.
###<tbody> :The body should sit inside the <tbody> element. 
### <tfoot> :The footer belongs inside the <tfoot> element.
### You can make cells of a table span more than one row or column using the rowspan and colspan attributes. 

# ** JS /Chapter 3: “Functions, Methods, and Objects **

### this is example of how create object and write key and values inside it
### This example starts by creating an object using literal notation.
### var hotel = { 
### name: 'Quay',
### rooms: 40, booked: 25,
### checkAvailability: function() { 
### return this.rooms - this.booked; 
### } } ; 
### This object is called hotel which represents a hotel called Quay with 40 rooms (25 of which have been booked).
### Next, the content of the page is updated with data from this object. It shows the name of the hotel by accessing the object's name property and the number of vacant rooms using the checkAvail ability() method. 
### JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts. 
### Arrays and objects can be used to create complex data sets (and both can contain the other). 