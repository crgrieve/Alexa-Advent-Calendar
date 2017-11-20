# Alexa-Advent-Calendar
Advent calendar skill tutorial built for teaching kids to code

I would recommend this tutorial as a starting point on Alexa skills introducing how to set up accounts on AWS and Amazon developer portal:
https://developer.amazon.com/alexa-skills-kit/alexa-skill-quick-start-tutorial

Setup:

*Sign up/ log in to AWS Lambda: https://console.aws.amazon.com/lambda

*Select "create function"

*Give it a name and select "choose an existing role" -> "lambda_basic_execution"

*Save this and you will be taken to a code editor.

*Copy code from AdventSkill.js to this editor and save.

*Copy the ARN number at the top right corner, you will need this.

*Sign up/ log in to: https://developer.amazon.com/login.html

*Select Alexa from menu-> Get Started -> Add a New Skill

*Complete details, give it a name, etc

*The "Innvocation Name" is how you open your skill. So if you put in "advent calendar" you can open it by saying "Alexa, open advent calendar".

*Copy Intents.txt to the "Intent Schema" field.

*Click "Add slot type" and add "LIST_OF_DAYS" as the type, with a list of numbers between 1 and 30 in the "enter values" field. These must be on separate lines.

*Copy the contents of Utterances.txt file to "Sample Utterances" field.

*Click Next

*When it asks for the endpoint, you can past your ARN number copied from lambda function.

*Click Next

*Enable testing.

*If all set up ok, you should be able to enter text in the "service simulator". Enter "open door 1"

*If you have an Alexa device associated to your account you can say "Alexa, open advent" (or whatever your innvocation name was) then "open door 1".


Now what?

*Go back to your code editor on lambda function.

*Have a look at lines 77 and 81, you can copy these for each other day in December you want on your advent and add in a message for each day.

*Have fun!!!




