# <img src='https://raw.githack.com/FortAwesome/Font-Awesome/master/svgs/solid/graduation-cap.svg' card_color='#000000' width='50' height='50' style='vertical-align:bottom'/> Learning
Teach Mycroft knowledge and humor.

## About
This Skill helps to give Mycroft a personality, by learning new information that you provide. If mycroft didn't understand you, you can immediately train the previous request by saying "I want to explain"--then you do not have to do everything from the beginning.

## Examples
* "Do you want to learn something"
* "Do you already know this"
* "There you can learn something"
* "I show you something"
* "can you keep a secret"
* "I tell you something private"
* "Please do not say what I'm talking about"

* "I want to explain it"

## Credits
Andreas Reinle(@gras64)
dawnstar89 (@dawnstar89) for English localization

## Conversations
    Use Conversation 1

    you "Do you want to learn something"
    mycroft "I like to learn. Which category is it?"
    you "humor"
    mycroft "what is your question"
    you "do you know siri"
    mycroft "give me keywords"
    you "know siri"
    mycroft "what should I know about it"
    you "I have never seen her"
    mycroft "So I'm supposed to answer the question "do you know siri" with "I have never seen her"?


    Save Data To ~/.mycroft/skills/LearningSkill/public/humor/en-us/dialog/know.siri.dialog
    Save Data To ~/.mycroft/skills/LearningSkill/public/humor/en-us/vocab/know.siri.intent
    You can edit the path at home.mycroft.ai.

    Use Conversation 2

    you "how does jack norris pay for the tram"
    mycroft "i don't understand"
    you "that you should humor"
    mycroft "give me keywords"
    you "Juck tram"
    mycroft "what should I know about it"
    you "bach doesn't pay him at all"
    mycroft "So I'm supposed to answer the question "how does jack norris pay for the tram" with "bach doesn't pay him at all"


    Use Conversation 3

    you "recording my voice for 30 seconds"
    mycroft "i don't understand"
    you "use the audio-record skill"
    mycroft "I found a variable {time} you can give it to me"
    you "30 seconds"
    mycroft "should I add the sentence: recording my voice for {time}"
    you "yes"
    mycroft "Recording audio for 30 seconds"

    Use Conversation 4 

    you "how are you"
    mycroft "i am good"
    you "complete also sometimes your answers"
    mycroft "how would you say that Replace Varaiblen with your own placeholders such as time or temperature."
    you "better than you"
    mycroft "should I add the sentence: recording my voice for {time}"
    you "yes"

    Use Conversation 5

    you "can you edit your dialogues in personal skill"
    mycroft "I will tell you sentences. If I'm right say yes"
    mycroft "I am an open source artificial intelligence."
    you "yes"
    mycroft "how would you say that Replace Varaiblen with your own placeholders such as time or temperature."
    you "I'm just another AI developed by Mycroft"
    mycroft "should I add the sentence: I'm just another AI developed by Mycroft"
    you "yes"
    mycroft "do you want to continue?"
    you "no"



## Add a new category
If you want to add a new category, you just have to add a category under mycroft ai. Mycroft will then ask you for the name in your language.

## todo
Dialog_Match: Support recognition of vocab files
Fallback: load your own intentfile into suitable skills


## Category
**Entertainment**
Information
Productivity

## Tags
#learning
#science
