# Code-along: Generating a "Morning update" using APIs

In this code-along, we'll use Python to combine several APIs to generate an MP3 file with a "morning update" to enjoy each day with our coffee. Our goal is to create an personalized "daily update" message that includes today's weather forecast and the ten most significant news headlines.

We will gather all the necessary information for our message from NewsAPI and Meteosource, two free online services that offer API access. Then, we'll use a custom prompt with the **OpenAI chat completions API** to generate an engaging message. Finally, we will send this message to the **OpenAI text-to-speech API** to generate an audio file of the message being read aloud and save it to our workspace so we can download and listen to it.
