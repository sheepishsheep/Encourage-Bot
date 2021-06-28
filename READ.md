Testing Discord Bot apps Responsive Discord bot that "encourages" using an adjustable database of encouragments and access ZenQuotes and GIHPY APIs.

Command responses are as follows:

user input: "$hello", bot response: "hello"

user input: "$inspire", bot response: a random quote from the Zen Quotes API

user input: "I'm needy", bot response: a random "I love you" gif from the GIPHY API

user input: "$new" followed by a phrase, bot response: adds phrase after "$new" to database of encouragments

user input: "$del" followed by existing phrase in encouragements database, bot response: deletes selected phrase

user input: "$list", bot response: list current database of encouragments

user input: "responding" followed by "true" or "false", bot response: turns responding on/off based on if input true/false