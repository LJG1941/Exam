![CodeCrunchText](https://github.com/LJG1941/Exam/assets/158084190/f72422d7-60ed-4d76-ba51-70e639c02ed4)
# Exam
Module2Exam
Requirements

Code Crunch

Have a Bite, while you Code

Logo for Your New Page
Your task is to recreate this webpage for CodeCrew's newest division called CodeCrunch. The required features are detailed below.

REQUIREMENTS

In your new page, make the following Updates:

The Main element should contain a custom layout.
User Story: The user should find themselves on a page detailing CodeCrunch in the main element, Code Resources should remain available in the left sidebar, a new feature will be implemented in a right sidebar that you will be building.
Note: Include at least 1 image, the provided './assests/CodeCrunch.jpg' is fine. AI generated or otherwise sourced is also welcome if time permits.
The Main element shouldn't contain the instructions from this page.
To the right of this blue box, add a new sidebar that has the following Features:

The Sidebar should be the same height as the current sidebar and main content areas
The Sidebar should have 1 Button that opens a prompt box
User Story: Upon clicking the button, a Prompt should ask the user for their (first) name
Note: Whatever the user enters should be stored in a variable that will be accessible to future functions
The Sidebar should have 1 Button that open an alert box
User Story: Upon clicking the button, an Alert box should contain a greeting (of your choice) that is addressing the User
Note: This greeting should be concatenated with the variable created from the prompt box
Example text for the alert box: Salutations, DJ!
The Sidebar should have 1 Form that generates food orders
User Story: The user should be able to select how many burgers and how many drinks they want to order
Upon clicking the button, their order should be added to an array of order objects and displayed on the page
Each order should have a button to remove it from the page
Note: In the browser, each order should look like:
 Kel, 🍔🍔, 🥤🥤 Deliver 
If an item is ordered 3 times or less in a single order, show an emoji for each item.
For item quantities 4 and above, display the single emoji followed by x and the quanity.
Examples: 🍔x4, 🥤🥤🥤, 🥤x5, 🍔
In code, each order should look like:
{ Name: Kel, Burgers: 2, Drinks: 2, Delivered: false} 
The name on the order should be populated by the Prompt box
The Form should not refresh the page when submitted
The Deliver Button should remove the order from the page and set the order object's Delivered property to true
The Sidebar should have 1 button to output all order details to the console
User Story: Upon clicking the button, the user should see order details in the following format in the Browser Console:
Total Orders: 10, Total Burgers: 12, Total Drinks: 14
Total Delivered: 8
Total Undelivered: 2
