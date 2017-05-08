# test
Information regarding test cases: 

	//Test 1 and 2 are test with correct use of the site with minor irregularities to simulate a real user 
	//No Price and no food type exclude the food and price parameters
	//test 3 inconsistent results caused an issue on two occasions where no results were gathered by yelp
	//test with yelp click is a test in which the script clicks on the link to the yelp page of the business
	//two searches + yelp click involves two searches of different parameters in which the the second search ends with the clicking of the yelp link

	Self Explanatory Tests:
		//Wrong zip
		//No zip 
		//Only price
		//Only radius
		//Only food type 

Test Result Report
	Bugs/Issues:
		 -Randomizer is either not functioning or not implemented yet.
		 -Site does not have appropriate response for empty paramater search.
		 -If zipcode is not input correctly or if there is no zipcode then the page just takes you to the intermediate page where you may not proceed with the button press.
		 -Test 3 produced a no results found at times.
