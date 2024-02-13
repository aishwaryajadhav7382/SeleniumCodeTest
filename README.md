# SeleniumCodeTest
Coding Solution

Instructions to run the solution:

1. Double click on testng.xml file under BEGINNINg folder to execute all three tests I have written in this solution.
2. First Test will navigate you to nykaa website and verify menus of the website. I have used Assettrue to verify the text of menus with equalsignorecase.
3. Second Test will navigate you to the Brands menu to search one of the brands listed in their website which is "Maybelline New York". After Searching the Brandname solution will click on the searched brandname and then verifying header of Searched results page.
4. The Third Test will navigate first you to Search brand like we did in second test and then it will continue next sceanrio once you get the search results for "Maybelline New York" . The test will proceed ahead with price selection filter. Webdriver will click on Rs.0- Rs.499 checkbox to filter out the products. Stroing the count of products filtered for further verifications.
5. This solution is equipped with maven and testNg dependencies.
6. Used POM concept to achieve abstraction. Created three page classes and imported those in main test class.
7. Also Used Implicit and explict waits whereever required.
