# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques

                                                                           
### REGISTER NUMBER : 212222110033
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 1 with Straightforward Prompts, Tabular Format Prompting and Preceding Question Prompting  

## 1. Use of Straightforward Prompts
Definition: Straightforward prompts are direct instructions or queries without 
ambiguity, designed to elicit clear responses from the AI.
Scenario: Order Tracking
Overview
This scenario involves a customer reaching out to the AI chatbot with a concern about 
their online order—typically asking where it is, when it will arrive, or why it’s 
delayed. This is one of the most common and essential use cases for customer service 
bots in e-commerce and logistics.
# Customer Query Example
“Hi, I ordered a pair of shoes last week and haven’t received them yet. 
Can you help me track my order?”
Chatbot Actions in This Scenario
# The chatbot needs to:
Identify the user's intent – in this case, order tracking.
Authenticate or retrieve order details using the order number or user profile.
Respond with the current status of the order (e.g., "In Transit", "Out for 
Delivery", "Delivered").
Handle follow-ups, such as delays, missed deliveries, or refund requests.
Use of Prompting Techniques
# Straightforward Prompt
The bot uses a direct query like:
“Check order #54321 status and provide delivery update.”
# Tabular Format Prompting:
If the order is delayed or has issues, the bot provides a table of causes and solutions:
Issue Reason Next Step
Delivery Delayed Weather disruption Update ETA, notify user
Not Found in System Invalid order ID Ask user to recheck order number
Package Lost Courier misplacement Escalate to human support
# Preceding Question Prompting
If a user replies, “It says delivered but I didn’t get it,” the bot continues 
naturally:
“Sorry about that. Could you please check with neighbors or 
the security desk first? If not found, I’ll help you file a missing 
item report.”
# User Input:
"Where is my order #54321?"
Straightforward Prompt to AI:
Track the status of order number 54321 and provide a clear update on its current
location and estimated delivery date.
# Chatbot Response:
"Your order #54321 is currently in transit and is expected to be delivered on May 27, 
2025. It's presently at the Chennai Sorting Facility."
2. Tabular Format Prompting
# Definition: This technique organizes information in rows and columns for easier 
comprehension, especially useful for comparing options or summarizing features.
Scenario: Product Troubleshooting - Phone not charging
# User Input:
"My phone isn't charging. What should I check?"
# Tabular Format Prompt to AI:
Provide a table listing common phone charging issues, possible causes, and 
recommended solutions.
# Chatbot Response:
Issue Possible Cause Recommended Action
Charging cable not working Damaged/loose cable Try a different, certified cable
Adapter issue Faulty power adapter Use a different adapter
Port blocked Dust/debris in port Gently clean the charging port
Software glitch System bug Restart the phone
Battery health issue Degraded battery Contact support for battery check
Customer Query Example
“Hi, my phone isn’t charging at all. What should I do?”
Chatbot Actions in This Scenario
# The chatbot needs to:
Understand the problem clearly from user input.
Diagnose the issue by asking follow-up questions or providing a checklist.
Offer actionable solutions, often one at a time.
Use visual aids or tabular data for better clarity.
Escalate to human support if the issue remains unresolved.
## Use of Prompting Techniques
# Straightforward Prompt
“Guide the user through basic troubleshooting steps for a phone 
that won't charge.”
# Chatbot Output:
“Let’s check a few things. First, can you confirm if you’ve tried using a 
different charging cable?”
# Tabular Format Prompting
When listing causes and fixes, the bot uses a clear table:
Possible Cause Explanation Solution
Damaged Charging 
Cable
Cable might be worn or 
broken
Try a certified replacement 
cable
Dust in Charging 
Port
Debris blocking 
connection Gently clean with a dry brush
Power Adapter 
Faulty
Adapter may be short￾circuited Use a different adapter
Software Glitch Phone’s OS might be 
stuck Restart your phone
Battery Issue Battery is no longer 
functional
Visit service center or contact 
support
# Preceding Question Prompting
The chatbot adapts responses based on user replies:
User: “Yes, I tried a different cable but it still doesn't work.”
Chatbot: “Thanks for confirming. Let’s check the charging port. Can 
you see any dust or debris inside?”
If user says “No”:
“Alright. As a next step, please try restarting your phone. Let 
me know if it charges after that.”

# 3. Preceding Question Prompting

Definition: This technique structures the prompt based on the preceding question or 
conversation context, making the chatbot’s responses feel more natural and 
conversational.
Scenario: General Inquiry - Return Policy
User Input:
"Can I return a product I bought last week?"
# Preceding Question Prompt to AI:
vbnet
Based on the user's question about returning a product, explain the return policy for 
orders made within the last 7 days.
# Chatbot Response:
"Yes, you're eligible for a return. Products purchased within the last 15 days can be 
returned, provided they are unused and in original packaging. Would you like me to 
initiate a return request?"
# Follow-up User Input:
"Yes, please initiate the return."
# Follow-up Prompt:
Initiate return request for the last order. Confirm details and guide the user through the return process.
# Chatbot Response:
"Return request initiated for Order #56984. Please pack the item securely and use the 
return label sent to your email. A pickup is scheduled for tomorrow."
# Customer Query Example
“Can I return a product I bought last week?”
# Chatbot Actions in This Scenario
The chatbot needs to:
Recognize the user’s intent — understanding return eligibility.
Provide accurate information based on company policy.
Check purchase date to determine return validity.
Guide user through the return initiation process.
Offer escalation if the user is confused or faces issues.

## Use of Prompting Techniques

Straightforward Prompt
“Tell the customer if they can return an item purchased 7 days 
ago, and explain how.”
Chatbot Output:
“Yes, you're eligible for a return. Our policy allows returns within 15 days of 
purchase if the item is unused and in its original packaging.”

## Tabular Format Prompting:

The chatbot can summarize return eligibility rules in a table:
Condition Eligibility Action Required
Purchased within 15 days ✅Yes Start return via chatbot or app
Used product ❌No Return not accepted
Without original packaging ❌No Packaging must be intact
Received damaged or wrong 
item ✅Yes Upload photo and raise 
complaint

## Preceding Question Prompting

The chatbot adapts to user follow-ups:
User: “Okay, how do I return it?”
Chatbot: “I can help with that! What’s your order number?”
“Return request for Order #44519 has been initiated. Please pack the 
item securely. A pickup will be arranged in 2 days.”

## Conclusion

Using a combination of prompting techniques:Straightforward Prompts streamline simple queries like order tracking.Tabular Format Prompting enhances clarity during technical troubleshooting.Preceding Question Prompting ensures smooth, context-aware conversations.This diverse prompting strategy makes the chatbot efficient, informative, and userfriendly, thereby improving the overall customer experience

# Result: Thus the Prompts were exected succcessfully.

