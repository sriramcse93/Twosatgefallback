## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## default fall
* bot_challenge
  - action_default_fallback
  
* outlook_issue
  - action_default_fallback

## outlook closed
* outlook_issue
  - utter_outlook_issue
* outlook_closed
  - utter_outlook_closed
* outlook_xml_error
  - utter_outlook_xml_error
