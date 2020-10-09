# HW3: Spooky Text
**SI669 Fall 2020**

## Video Walkthrough
See the [Demo Video](https://youtu.be/FHCFFEClyG4).

## Learning Goals
This homework will give you practice working with user input and conditional display

## Project Goals
Fill in the missing code to complete an app that accepts text input from the user and can display the text in different ways depending on the settings of two Switches.

## What to Do
1. Accept the GitHub Classroom invitation.
2. Clone this repo to your local machine.
3. `cd` into the directory that was created when you cloned the repo (it should be called `hw3-spookytext-<your-github-id>`).
4. Run `yarn install` to install all dependencies.
4. Implement `handleChangeText()`, `handleReverseText()`, and `handleReverseColors()`. You shouldn't need to change anything else, but you can if you want.
5. Push your final changes to GitHub before the deadline.
6. Create a screencast video and submit the link to Canvas before the deadline.
7. Indicate in your Canvas comments which requirements (including extra credit) you believe you met.

## Notes
* Be sure to show that the switches can operate independently. 
* Also show that existing text is reversed when the "Reverse Text" is switched "On" and that new text is reversed when the  switch is already on.
* A `reverseText()` function is provided. This will come in handy.

## Grading (up to 120 points)
| No. | Requirement  | Points |
| --- | ------------- | ------------- |
| 1 | Switches change state when pressed | 20  |
| 2 | TextInput displays user input | 20 |
| 3 | Result Text updates when TextInput changes | 20 |
| 4 | Colors are inverted when 'Reverse Colors' switch is 'On' | 20 |
| 5 | Text is reversed when 'Reverse Text' switch is 'On' | 15 |
| 6 | Text is reversed correctly when 'Reverse Text' switch is 'On' and new text is entered | 15 |
| 7 | Switches operate independently of each other | 10 |
|   | **Total** | **120**

## Extra Credit
For extra credit you can implement a simple password validator that operates as shown in the [demo video](https://youtu.be/hztb3RzcziI). 

## Notes
* You may notice that the starter app uses a [KeyboardAvoidingView](https://reactnative.dev/docs/keyboardavoidingview). It does what the name 
suggests. You may need to read the docs to understand what it's doing so you can get the password panel to render correctly.
* You may also want to read to read the [TextInput docs](https://reactnative.dev/docs/textinput), if only to get the "password" behavior shown in the video.
* The password checker shown in the video only checks the top box for the correct characters (letters, numbers, etc.). Whether passwords "match" is evaluated whenever **either** password box is modified.

## Grading (up to 4 points)
| No. | Requirement  | Points |
| --- | ------------- | ------------- |
| 1 | Passwords are obfuscated  | 0.5  |
| 2 | Password area layout responds reasonably well when keyboard is shown and hidden | 0.5 |
| 3 | "contain only letters and numbers" is correctly updated based on the contents of the top password box | 1 |
| 4 | "contain at least one upper case letter, lower case letter, and number" is correctly updated based on the contents of the top password box | 1 |
| 5 | "match" is correctly updated based on the contents of **both** password boxes | 1 | 
|   | **Total** | **4**

