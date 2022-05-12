# Sentence Paraphraser & Translator
This package is created to aid research of chatbots and online health interventions, although it can be used in other ways. When designing these sort of systems, a large variety of stimuli that is delivered to users is needed. \
For example, when creating a platform that sends messages to users to incentivise them to perform a certain healthy behaviour, a very large corpus of messages is needed. Users can become annoyed if they receive the exact same messages repeatedly. It will also feel unnatural to have the chatbot or platform send out the exact same messages. Real speech is very diverse. \
This packages aims to help with that by generating alternative versions of a sentence. By having various paraphrases automatically generated, we can easily increase the message corpus that is available to researchers designing these systems and, thus, increase their effectiveness.\
Additionally, these projects are often done in collaboration with other research labs, universities, and even countries. So, being able to also translate these messages quickly is also valuable.\
\

### How to use it ###
The user will be asked to input a sentence into a text box. They will then have two bottond to choose from. They can click the paraphrase button which will trigger the apperance of a slider to choose to paraphrase their sentence in 1 to 3 different ways. They can also click the translate button. This will trigger the appearance of 3 new buttons to choose the language(s) they wish to translate their sentence to. The options are German, Spanish, and Dutch.\
Users will view the output as a table on their screen. They will also have a button that will allow them to download their table in a csv file to be used in their projects.\
\

### Features ###
* **Paraphrasing** - This will generate 1 to 3 paraphrases of the sentences the user as inputted. The number of sentences the user wants will be able to be selected with a simple slider after they have selected the paraphrase button.
* **Translating** - The available languages will be German, Spanish, and Dutch. This is because of the relevance to my own online health intervention project, but more languages can be added in the future for broader applications.\
\

### How it is made ###
This package will be made with R Studio and R Shiny Apps.\
This means the output will be an interactive web app.

