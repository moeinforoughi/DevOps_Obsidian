A part of [[DevOps]] learning path
 A part of [[Git]]

- We must don't let bugs and errors go to product with tests 

1- Functional Tests -> 
	1- Unit Test -> test a new part of code single 
	 2- Integration Test -> test new part of code beside other parts 
	 3- Smoke Test -> do apart of test to just see the results
	4- Functional Test -> test a specific function of our app ( *specific flow of our app )

2- Non-functional Tests ->
	1- Load Test -> send number of virtual users to our product to test how it tolerate the user load
	2- Volume Test -> send more traffic than our estimated user load to see reactions of our servers 
	3- Stress Test -> send loads to servers until down 
	4- End-To-End Testing -> we completely simulate flow of the user on our product 

( *Fast Fail => Fail in tests is better than fail on product )