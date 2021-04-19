# ML Engineer Mini Project

# value_of_the_question
model to predict the value of the question in the TV game show “Jeopardy!”

# Step 1:
## Problem Statment
Build a model to predict the value of the question in the TV game show “Jeopardy!”.

Data can be downloaded from this link: https://www.kaggle.com/tunguz/200000-jeopardy-questions

Data description:
'category' : the question category, e.g. "HISTORY"

'value' :  𝑣𝑎𝑙𝑢𝑒𝑜𝑓𝑡ℎ𝑒𝑞𝑢𝑒𝑠𝑡𝑖𝑜𝑛𝑎𝑠𝑠𝑡𝑟𝑖𝑛𝑔,𝑒.𝑔." 200" (Note - "None" for Final Jeopardy! and Tiebreaker questions)

'question' : text of question (Note: This sometimes contains hyperlinks and other things messy text such as when there's a picture or video question)

‘answer' : text of answer

‘round' : one of "Jeopardy!", "Double Jeopardy!", "Final Jeopardy!" or "Tiebreaker" (Note: Tiebreaker questions do happen but they're very rare (like once every 20 years)

'show_number' : string of show number, e.g '4680'

'air_date' : the show air date in format YYYY-MM-DD

# Step 2: 
I found two issues:
- There is no option to reply to particular chat
- When bot is summarizing the above user’s conversation it is not comparing and eliminating the same chat sentences  
