Zeyun's Chatbot

Description of the Program

     This is a code for a telegram chatbot that can answer the answers about covid-19. 
     To use this chatbot, install the Telegram on your device and go to this link "t.me/Zeyun_Chat_bot", and you can find the chatbot named "my_chatbot".
     Run this code, and type "/start" in the chat window. When you see a prompt "Hello, What do you want to know about Covid-19?", you can ask your question.
     You can ask questions about a specific case type in a specific country and around the glove. You can also ask for the cases outside a specific country.
     The chatbot will only answer the covid-19 related questions to you. If the chatbot do not respond, please rephrase your question.

Description of the code
     
     The code is based on Python programming, and it uses external resources, so please run the code when WIFI is connected.
     This bot used the "Covid" API online and the data of the "worldmeter" website. This time will update the current new confirmed cases and deaths updated at this time today.
     Thus, the respond will be 0 if you want to check the new confirmed cases and deaths since the official number may not updated on the website. 
     This program also used the resources, such as "Spacy", "rasa", "covid", and "telegram". If you use Colaborator to open the file, you can just directly run the code.
     If you use other software program, like "Jupyter Notebook", please install these resources on your own computer before you run the code.
     
     The code uses Spacy and defalt programmed intentions and entities so that it can recongnize the important phrase about covid-19 questions. Spacy can tell the countries in your sentence.
     The code can also tell some of the denial intentions in your sentence. Since the question sentense is assumed easy and only relative to countries, the code only uses the easiest way to extract the denial intention.
     
