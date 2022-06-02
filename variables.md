Long form with initilization
 
  	var i int = 10
	var s string = "superman"


Long form without initilization
  
  	var i int
	var s string

	i = 10
	s = "superman"


Declaration with implcite inference

  	var i = 10
	var s = "superman"


Short form

  	i := 10
  	s := "superman"
  

Declaring multiple variables at a time

  	a, b, c := 10, 20, 30
  	s1, s2, s3 := "superman", "batman", "spidreman"

Zero Values
If you declare a variable without assigning it a value, Golang will automatically bind a default value (or a zero-value) to the variable.
