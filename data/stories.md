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

## sad path 3

* greet
    - utter_greet
* mood_unhappy
    - utter_cheer_up
    - utter_did_that_help
* affirm
    - utter_happy

## car request

* mood_great
    - utter_disambiguate_model

## New Story

* purchase_query
    - utter_disambiguate_model

## New Story

* purchase_query
    - utter_disambiguate_model

## New Story

* purchase_query
    - utter_disambiguate_model

## Welcome

* welcome
    - utter_welcome_message
