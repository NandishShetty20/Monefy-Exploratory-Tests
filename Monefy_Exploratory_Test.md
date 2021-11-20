
# **Exploratory Tests for Monefy APP In Android)**

**Objective**: Do a High Level Testing of Monefy App to check if the Application works as expected.

**Version**: 1.13.0

**Android OS Version**: 10

Exploratory tests are usually ad-hoc tests which are not bound to any test case steps. They are testes on the fly.The focus of exploratory testing is more on testing as a “thinking” activity.Exploratory Testing is widely used in Agile models and is all about discovery, investigation, and learning. It emphasizes personal freedom and responsibility of the individual tester.Below mentioned are the steps I followed for Money App's explorator testing,

1. When Monefy app icon is clicked, it should launch the application.(High)
   1. The look and feel of the app should be easy on the users eyes. (High)
   2. The icons should be displayed properly.(Medium)
   3. The header of the application should be present at the top of the application. (Medium)
   4. There should be a navigation icon, search icon, transfer icon and vertical ellipsis icon displayed at the top.(High)
   5. The main menu should have expense icon and income icon displayed at the bottom of the app.(High)
   6. Balance amount, expense amount and Income amount should be displayed on the main menu page.(High)
   7. Expense icons should be displayed in the main menu.(Low)
2. When user clicks on the vertical ellipses button, it should open a sub menu on the Right-Side.(High)
   1. Sub Menu should have Categories, Accounts, Currencies and Settings buttons.(High)
   2. Each button should take the user to the corresponding menu.(High)
   3. Categories button should open a list of all the default expense and income options.(High)
      - Category list should close when the user click on the categories button again.(Low)
      - The user should be able to add a new expense or income option.(Pro Feature)(Medium)
      - Clicking on an expense/income option should take the user to the edit category page.(High)
      - The user should be able to rename a category in edit category page which should save automatically.(High)
      - The user should be able to edit the icon of a category. (Pro Feature)(Low)
      - The user should be able to delete a category.(High)
      - User should exit the category page by clicking on android back button.(High)
      - A toast message should appear with Category was updated message and should contain a cancel button which 
        should cancel the changes made. (High)
   4. Accounts button should open a list of all the accounts in the app.(High)
      - Account Add button, Account list and Tranfer button should be listed.(High)
      - User should navigate to edit account window when clicked on an account.(High)
      - User should be able to edit the name, account balance, date and account icon. (High)
      - The details entered should auto save. (High)
      - A toast message should appear with Account was updated message and should contain a cancel button which 
        should cancel the changes made. (High)
      - User should be able to add a new account when clicked on Add button. (High)
      - User should be able to add a name, account balance, date and account icon.(High)
      - User should be able to select the currency.(Pro Feature)(High)
      - A toast message should appear with New Account was added message and should contain a cancel button which 
        should cancel the changes made. (High) 
      - The user should be able to tranfer amount between accounts when clicked on transfer button.(High)
    5. User should be able to access Currencies tab when clicked on Currencies button.(Pro Feature) (High)
    6. Settings button should open the list of in app settings.(High)
       - User should be able to change the language of the app by clicking on Language button. (High)
        (Bug: When a new language is selected the format of the amount displayed is changed. The comma and the decimal symbols interchange.)
       - User should not be able to change the Currency of the app as it is not a Pro App. (High)
        (Bug: Currently the user can change the currency)
       - User should be able to Synchronise the app with Dropbox and Google Drive. (Pro Feature)(Medium)
       - User should be able to take data backup, restore data and clear the data in the app. (High)
3. User should see side menu with time period settings when clicked on Navigation icon on the leftmtop corner.(High)
   1. User should be able to switch between acounts by clicking on the dropdown and selecting the account.(High)
   2. User should be able to acces accout details by swiping between dates when date period is selected. (High)
   3. User should be able to access account details by swiping between a weeh ranges when week period is selected. (High)
   4. User should be able to access account details by swiping between months when month period is selected. (High)
   5. User should be able to access account details by swiping between years when years period is selected. (High)
   6. User should see all his account details from the first day when All period is selected. (High)
   7. User should be able to see the account details of a specific interval when interval period is selected. (Medium)
   8. User should be able to see the account details of a specific date when Choose date is selected. (medium)
   9. User should be able to close the navigation side menu by clicking on the back button on the app.(Low)
4. User should be able to search the details entered when clicked on the search icon. (High)
   1. User should see all the transaction details for the entered category with specific dates. (Medium)
5. User should be able to access the new transfer screen when clicked on the transfer icon(double arrow mark). (high)
   1. User should see the date in format "Weekday, DD Month" and should be able to select the date when clicked on it. (High)
   2. User should be able to add a note.(Medium)
   3. User should be able to select from account and to account.(High)
   4. User should be able to add an amount((should be > 0) with the help of numeric key pad.(High)
     (Bug: The numeric key pad should only contain numbers, decimal point and not mathematical symbols. Also, the user should not be able to do arithematic 
     operations inside the text box.)
   5. The user should be able to add a new transfer when clicked on Add Transfer button. (High)
   6. A toast message should appear with Transfer was added message and should contain a cancel button which 
      should cancel the transfer. (High) 
6. User should be able to access New Expense window by clicking on the category icons in main menu.(High)
   1. User should see the date in format "Weekday, DD Month" and should be able to select the date when clicked on it.(High)
   2. User should be able to add an amount(should be > 0) with the help of numeric key pad.(High)
     (Bug: The numeric key pad should only contain numbers, decimal point and not mathematical symbols. Also, the user should not be able to do arithematic 
     operations inside the text box.)
   3. User should be able to add a note.(Medium)
   4. The user should be able to add the expense when clicked on Add 'category' button. (High)
   5. A toast message should appear with category_name: amount added message and should contain a cancel button which 
      should cancel the new expense added. (High) 
   6. User should be able to go back to main menu without adding any expense using the app back button.
7. User should be able to access New Expense window by clicking on the New Expense icon('-' sym inside a circle) from main menu.(Medium)
   1. User should see the date in format "Weekday, DD Month" and should be able to select the date when clicked on it.(High)
   2. User should be able to add an amount(should be > 0) with the help of numeric key pad.(High)
     (Bug: The numeric key pad should only contain numbers, decimal point and not mathematical symbols. Also, the user should not be able to do arithematic 
     operations inside the text box.)
   3. User should be able to add a note.(Medium)
   4. User should be able to select the category of the expense by clicking on choose category button. (High)
   5. User should be able to access the category icon. (High)
   6. User should be able to create a new category by clicking on add button.(Pro feature)(Medium)
   6. User should be able to add the expense to the slected date when clicked on the category icon. (High)
   8. A toast message should appear with category_name: amount added message and should contain a cancel button which 
      should cancel the new expense added. (High)
8. User should be able to access New Income window by clicking on the New Expense icon('+' sym inside a circle) from main menu.(Medium)
   1. User should see the date in format "Weekday, DD Month" and should be able to select the date when clicked on it.(High)
   2. User should be able to add an amount(should be > 0) with the help of numeric key pad.(High)
     (Bug: The numeric key pad should only contain numbers, decimal point and not mathematical symbols. Also, the user should not be able to do arithematic 
     operations inside the text box.)
   3. User should be able to add a note.(Medium)
   4. User should be able to select the category of the income by clicking on choose category button. (High)
   5. User should be able to access the category icon. (High)
   6. User should be able to create a new category by clicking on add button.(Pro feature)(Medium)
   7. User should be able to add the income to the selected date when clicked on the category icon. (High)
   8. A toast message should appear with category_name: amount added message and should contain a cancel button which 
      should cancel the new income added. (High)
9. User should see the income amount and the expense amount at the center of the app inside a circle.(High)
   1. Whenever an expense is added to a particular date, the user should see the expense amount update at the center for the same date. (High)
   2. Whenever an income is added to a particular date, the user should see the income amount update at the center for the same date. (High)
10. User should see the balance amount based on income and expense amounts. (High)
   1. User should see all the transaction entries namely, transfer, expense and income amount when clicked on the Balance amount button. (High)
   2. Balance amount can be accessed based on the time period selected in the navigation tab(Date,Week,Month..). (High)


From the above analysis of the Monefy app, the app seems to be stable.There are minor defects which are not a show stopper for the application.I have marked the tests as High,Medium and Low based on their effect on the application usage.Since the app is a money management app the window for any issues or bugs should be very minimal.So most of the tests are marked as High priority tests. There are a lot of interactive elements, ui elements in the Application. Instead of concentrating on the UI part more time should be spent on testing the functionality.Since I only have one andoird device the testing of the app was limited. The app still needs to be tested in different Models,OS and Network conditions.



**App Risks**:

1. Insecure Communication: In a common mobile app, data is typically exchanged in a client-server fashion. When the application transmits data, it traverses through the internet and the mobile device’s carrier network.To prevent Insecure communication establish a secure connection after authenticating the identity of the endpoint server. While applying SSL/TLS to the mobile application, make sure to implement it on the transport channels that the mobile app will use to transverse sensitive data such as session tokens, credentials, etc.

2. Lack of Input Validation: Input validation is the process of assessing input data to ensure that it is properly formed, preventing malformed data that might consist of harmful code or may trigger malfunction in the mobile app.To implement input validation we can use programming techniques that facilitate the effective enforcement of data correctness such as:  
 - Minimum and maximum value range check for dates and numerical parameters along with length check of strings
 - Input validation against XML Schema and JSON Scheme

3. Insufficient Authentication and Authorization Controls: Missing or poor authentication schemes allow attackers to anonymously execute functionalities within the mobile application or the backend server used by the app. To prevent authentication issues ensure hat authentication requests are performed on the server side. Upon successful authentication, the data should be loaded into the mobile device. This will ensure that data is only loaded after successful authentication.

4. Poor Encryption: Encryption is the process of converting data into an encrypted form that is only readable after it has been translated back using a secret decryption key. If devices and data are not encrypted properly,then attackers can much more readily access the data.Poor encryption can lead to data loss and all of the repercussions that follow from that loss of information.we need to make sure to implement modern encryption algorithms that are accepted as strong by the security community.

5. Reverse Engineering:If an attacker can read the app's code, they can find better ways to attack the application. Reverse engineering can be used to determine how the app functions on the back end, modify the source code, expose encryption algorithms in place, and more. So the code that is developed for the mobile app can be used against the app and pose severe security risks.An effective way of preventing mobile apps from reverse engineering is to limit the capabilities client side and expose more functionality through web services server side.



    
 
    
