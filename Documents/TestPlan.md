# Test Plan and Results
## Part 1:

To accomplish our testing, we will be dividing our process into three distinct areas-- front-end testing, back-end testing, and “mixed” testing. There are multiple reasons to divide the testing this way: this can promote clear organization for our process, our project is already sorted into these three distinct areas, and it will allow us to divide the work for testing more easily between our group. For our initial testing, we will focus on basic, surface-level testing for the front-end to ensure proper input and display, as well as testing through postman in the backend to ensure our functions are working properly. To be as comprehensive in our testing as possible, we will need to use a combination of normal and abnormal testing, with a focus on functional testing. We would then expand our test from a small testing database to a larger one, repeat our testing, and then work on implementing our API scraping for our database. After this point, we would move to testing the “mixed” areas of our project, where the two different ends need to communicate. The results displayed will need to be tested through a combination of functional and performance testing to verify correct and adequate results.

## Part 2:

 * Get all books test backend
     - 1
     - This test is used to verify that the books can be accessed from the backend
     - The tester is to use postman to endet the url on a get request. The test will output the books in the database
     - A url of of the local host and get request
     - A list of books from the database
     - normal
     - whitebox
     - functional
     - Unit
     - pass
 * Get set number of books backend
     - 2
     - This test is used to verify that the right number of books can be pulled from the backend
     - The tester is to use postman to endet the url on a get request. The test will output the books of a set number
     - A url of of the local host and get request
     - A list of books from the database of a set number
     - normal
     - whitebox
     - functional
     - Unit
     - pass
 * Get set genre of books backend
     - 3
     - This test is used to verify that the right genra books can be pulled from the backend
     - The tester is to use postman to endet the url on a get request. The test will output the books of a set genre
     - A url of of the local host and get request
     - A list of books from the database of a set genre
     - normal
     - whitebox
     - functional
     - Unit
     - pass
* Get set length of books backend
     - 4
     - This test is used to verify that the right length of books can be pulled from the backend
     - The tester is to use postman to endet the url on a get request. The test will output the books of a set length
     - A url of of the local host and get request
     - A list of books from the database of a set length
     - normal
     - whitebox
     - functional
     - Unit
     - pass
 * Ui element reliability front end
     - 5
     - This test will be used to ensure the visual integrity of our application in a variety of situations.
     - The test will be carried out by using a variety of situations in which the application can be used, including screen/window sizes, resizing of the web interface, and the intersection of certain UI elements under particular circumstances.
     - Input: a variety of user-caused inputs in the interface.
     - Output: The visual/functional impact on the UI.
     - Normal & abnormal
     - Whitebox
     - Functional & performance
     - Unit
     - pass
 * Correct input handling frontend
     - 6
     - This test will process the input handling from a user.
     - This test will be carried out by using a variety of user criteria in their query.
     - Input: A set of criteria from the user
     - Output: A formatted version of the criteria
     - Normal
     - Blackbox
     - Functional
     - Unit
     - pass
 * Incorrect handling front end
     - 7
     - This test will verify the handling of invalid inputs from a user.
     - This test will be carried out by a user submitting a query with missing/incomplete data.
     - Input: Invalid query
     - Output: Some sort of error message/indicator, or an attempt to “standardize” the input if possible
     - Abnormal
     - Blackbox
     - Functional
     - Unit
     - pass
 * Pass info to fontend mix
     - 8
     - This test will verify whether the output from the back-end has been converted into a format useable for the front-end.
     - This test will be made by comparing received converted output with the expected converted output in a controlled setting.
     - Input: Unconverted backend data
     - Output: Converted backend data
     - Normal
     - Whitebox
     - Functional
     - Integration
     - fail
 * Display data frontend
     - 9
     - This test will check whether the information is being properly displayed to the user.
     - This test will be performed by verifying if the information displayed is visible, easy to digest, and accurate to the internal data being processed for display.
     - Input: Converted backend data
     - Output: Display of data
     - Normal
     - Blackbox & whitebox
     - Functional
     - Unit
     - fail
 * Pass infro to backend mix
     - 10
     - This test is used to verify that the criteria of the books are passed to the backend
     - The tester is to fill out the frontend boxes criteria then click get book list. Check the developer tools to see the console.log statement
     - The specified criteria like length and genre
     - A console log of the inputed data
     - normal
     - blackbox
     - functional
     - Integration
     - fail
