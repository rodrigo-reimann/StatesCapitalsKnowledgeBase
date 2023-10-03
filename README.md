# StatesCapitalsKnowledgeBase
Introduction:
The StatesCapitalsKnowledgeBase repository hosts two Java programs that test and facilitate user interaction with U.S. state-capital knowledge. While both programs serve to educate users about U.S. states and their capitals, they implement distinct methods and data structures to achieve their goals.

1. USStates:
Description:
The USStates program offers an interactive approach to test a user's familiarity with U.S. state capitals. The program begins by challenging the user to match a given capital with its state. Following this, it quizzes users on how many state capitals they can recall.

Features:

Contains a two-dimensional array listing U.S. states and their corresponding capitals.
Organizes the array alphabetically by state name.
Prompts the user to input a capital and then identifies the corresponding state.
In case of an incorrect guess, the program displays all state-capital pairs.
Introduces a quiz where users input as many capitals as they recall.
Usage:
Run the USStates program, follow the on-screen prompts, enter capital names, and participate in the quiz.

2. Part2_Hash:
Description:
The Part2_Hash program employs a HashMap to store and interactively retrieve state-capital pairs. It further showcases the transfer of this data into a TreeMap to maintain a sorted order of state names. On inputting a state name, the program provides the corresponding capital.

Features:

Utilizes a HashMap for efficient storage of state-capital pairs.
Displays the entire list of states and capitals.
Transfers the HashMap data to a TreeMap to ensure a sorted order based on state names.
Accepts user input of a state name and displays the associated capital.
Usage:
Execute the Part2_Hash program, observe the printed list of states and capitals, and when prompted, enter a state name to get its capital.

General Notes:
Both programs allow case-insensitive input, ensuring that users can input state or capital names in any letter case and still receive accurate feedback.
