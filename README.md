# Whatsapp-RSVP

## About

This is a RSVP bot for Whatsapp. It is able to record groups of people (and their attendees' number of pax) arriving to a particular event invited by the host. 
It makes it easier for the host to view at a glance:
- Each attendee's name along with number of pax
- Total number of pax

## How to use
Firstly, the host must link their Whatsapp account to the bot.
'!start' gives an overview of instructions
'!add Name Number' allows an attendee to add their name along with number of pax. Subsequent number changes to the same name will reflect the new value.
'!add Name 0' removes the attendee fromn the list
'!list' prints the list that shows each attendee's name along with number of pax, and the total number of pax
'!wordle GUESS' allows anyone to play a game of wordle, my original whatsapp chatbot function.

## Acknowlegements

This bot was built using [whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js), and taking inspiration from SCSE iLAB: [Create your own WhatsApp Chatbot workshop](https://github.com/LOLIPOP-INTELLIGENCE/Wordle-Workshop).
