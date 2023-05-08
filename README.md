Download Link: https://assignmentchef.com/product/solved-textanalyzer-java-program
<br>
The purpose of this assignment is to use String, StringBuilder, loops, if statements, and objects. The application in this assignment will create and manage a “block” of text. The Eclipse project will consist of two classes:

the application class named TextAnalyzerApplication

the service class named TextAnalyzer.

Details on each of these are provided below.

Create an Eclipse project named TextAnalyzer. Use a package name of edu.seminolestate.textanalyzer. (You can substitute your domain name for edu.seminolestate if you wish.) This project will have two classes – TextAnalyzer and TextAnalyzerApplication. The TextAnalyzerApplication class will have the main method.

The following requirements apply to the TextAnalyzer class. Here is the UML class diagram <img decoding="async" alt="UML Class Diagram for the TextAnalyzer Class TextAnalyzer textBlock: StringBuilder +DEFAULT TEXT BLOCK: String ADD_TO_FRONT: int + ADD_TO_BACK: int + TextAnalyzer (newText : String) + addSubString (addedText : String, frontOrBack: int): String getNumberOfConsonants (): int + getNumberOfVowels (): int + getNumberOfWords (): int +getText Block () :String + setTextBlock (newText: String) void " width="489" height="634" data-recalc-dims="1" data-src="https://i0.wp.com/d2vlcm61l7u1fs.cloudfront.net/media%2F3ba%2F3ba00373-bff4-4c0b-9fd8-9385a393705c%2FphpVJ6R9T.png?resize=489%2C634" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="" src="https://i0.wp.com/d2vlcm61l7u1fs.cloudfront.net/media%2F3ba%2F3ba00373-bff4-4c0b-9fd8-9385a393705c%2FphpVJ6R9T.png?resize=489%2C634" alt="UML Class Diagram for the TextAnalyzer Class TextAnalyzer textBlock: StringBuilder +DEFAULT TEXT BLOCK: String ADD_TO_FRONT: int + ADD_TO_BACK: int + TextAnalyzer (newText : String) + addSubString (addedText : String, frontOrBack: int): String getNumberOfConsonants (): int + getNumberOfVowels (): int + getNumberOfWords (): int +getText Block () :String + setTextBlock (newText: String) void " width="489" height="634" data-recalc-dims="1">

 </noscript>

Create a private variable named textBlock. This must be a StringBuilder.

Create three public class constants as shown in the UML class diagram. The constant values will be: ADD_TO_FRONT = 1; ADD_TO_BACK = 2; DEFAULT_TEXT_BLOCK = No user text available.

Create a constructor for the TextAnalyzer class. This constructor will have one parameter of type String. Use this parameter to update the textBlock by calling the set method.

Create a get and set method for the textBlock data member. The get method must return the value of textBlock as a String. The set method must have one parameter of type String. Use this value, if not null, to update the value of textBlock. Do nothing if the parameter is null. In other words do not update textBlock if the parameter is null.

Create a method to return the number of words in the textBlock. For our purposes a word will be defined as something followed by a space. This will be true for all words except the last word.

Create a method to return the number of vowels in the textBlock. For our purposes vowels will be a, e, i, o ,u, A, E, I O, U.

Create a method to return the number of consonants in the textBlock. This will be a count of all the letters in the textBlock except vowels.

Create a method to add a substring to the textBlock. This method must have a parameter for the substring to be added and a parameter to indicate whether the substring should be added to the front or back of the textBlock. Use the class constants (described above) for front and back.

The following requirements apply to the TextAnalyzerApplication class.

Display a menu like the one below when the application starts. Redisplay the menu after each option is process except option 6. Enable user to continue to process options except after option 6.1 – Create the text2 – Change the existing text3 – Display statistics for existing text4 – Add new text to existing text5 – Display existing text6 – Exit

Create a new TextAnalyzer object if the user picks option 1. Prompt the user to enter the new text for the TextAnalyzer object. Use a Scanner object to read the user input. Display the menu described above after you create the object.

Change the text in the TextAnalyzer object if the user picks option 2. Prompt the user to enter the new text. Use a Scanner object to read the user input. Do the update by calling the set method in the TextAnalyzer class.  Display an error message if the TextAnalyzer object has not been created. Display the menu described above after you finished the update.

Display the number of consonants, the number of vowels, and the number of words if the user picks option 3. Use the TextAnalyzer object to call the appropriate methods in the TextAnalyzer class.  Display an error message if the TextAnalyzer object has not been created. Display the menu described above after you finished displaying the information.

Add the new text entered by the user if the user picks option 4. Prompt the user to enter the new text. Also prompt the user to choose whether the new text should be added to the front of the existing TextAnalyzer object or the back. Use a Scanner object to read the user input.  Display an error message if the TextAnalyzer object has not been created. Display the menu described above after you finished adding the text.

Display the existing text from the TextAnalyzer object if the user picks option 5. Call the get method to retrieve the text. Display an error message if the TextAnalyzer object has not been created. Display the menu described above after you finished adding the text.

Display a closing message and end the application if the player selects the quit option (number 6). The application must continue to run until the player selects the quit option from the menu.

All input for this project must use a Scanner object. All output must be written to the console using System.out.