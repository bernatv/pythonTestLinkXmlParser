# pythonTestLinkXmlParser

## How to use

This is an easy python script to add a lot of testlink test cases in a easy way. 
It's only needed to create a .txt file with the tests cases data that you want to import inside a testsuite in xml format. 

### TXT source data

The txt file with the tests cases have to follow the next format:

    Create something
    	action1		expect1
    	action2		expect2
    	action3		expect3
    
    Create something2
    	action11	expect11
    	action22	expect22
    	action33	expect33
    
    Create something3
    	action12	expect12
    	action23	expect23
    	action34	expect34
    	
*Fist is needed the title of step and then the next line started with a tab goes the action and splited with another tab, the expect result. 

	
This example will add three test cases with actions and expected result for each one

Feel free to add improvements to the scripts please. 

