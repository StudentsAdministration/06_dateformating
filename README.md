# #6 Date formating
Date styling in the view and @DateTimeFormat(pattern = "yyyy-MM-dd") annotation in the model    

## Model
In the entities (here student.java class) you will need to specify the dataformat in order to make it work (be aquvalent) to the format in the view.    
 
 ````java   
 // needed for input field on html pages (in order to serve the right format)
 @DateTimeFormat(pattern = "yyyy-MM-dd") 
 private Date enrollmentDate;
 ````   

## View
* [Dates - utility methods for java.util.Date objects](http://www.thymeleaf.org/doc/tutorials/2.1/usingthymeleaf.html#appendix-b-expression-utility-objects)    


