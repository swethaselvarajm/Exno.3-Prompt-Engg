# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques

## DATE:                                                                            
## REGISTER NUMBER : 212222230155
## Aim: 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 1 with Straightforward Prompts, Tabular Format Prompting and Preceding Question Prompting Use Case: Customer Support in Retail Environment
## Objective:
To design and test an AI-powered chatbot that enhances customer experience in a retail setting by managing inquiries, solving issues, and guiding shoppers using a variety of AI prompting techniques.

## ALGORITHM
### Step 1: Define Use Case
Develop a virtual assistant that supports customers in a retail store (online or in-person) by handling product queries, complaints, availability checks, return/exchange policies, and promotional offers.

### Step 2: Define Prompting Techniques
Apply the following prompting strategies:

1.Direct Instruction
2.Contextual Prompting
3.Persona-Based Prompting
4.Few-Shot Prompting
5.Chain-of-Thought Prompting
6.Instruction with Constraints
7.Reflective Prompting

Step 3: Prompt AI Tools
Test each prompt using ChatGPT and Claude.

Step 4: Capture Outputs
Collect chatbot responses and assess tone, relevance, and helpfulness.

Step 5: Analyze Output
Evaluate the performance for clarity, emotional intelligence, user experience, and logical flow.

## PROMPTS & OUTPUT OVERVIEW – RETAIL CUSTOMER SUPPORT CONTEXT
### 1. Direct Instruction Prompting
Objective: Provide quick and specific responses to common retail questions.

Prompt:
"When a user asks, 'Is this item in stock?', reply: 'Yes, the item is available in our store. Would you like to place an order or check local availability?'"

| Platform | Output                                                                         | Analysis                                          |
| -------- | ------------------------------------------------------------------------------ | ------------------------------------------------- |
| ChatGPT  | “Yes, it’s currently in stock. Would you like me to help you with your order?” | Prompt followed precisely. Polite and clear.      |
| Claude   | “The item is in stock! Would you like to reserve or purchase it now?”          | Cheerful tone, accurate, slight added engagement. |

✅ Evaluation:
Accuracy: High
Speed: Instant
Customer Engagement: Claude added more action-oriented language

### 2. Contextual Prompting
Objective: Use previous interactions to tailor responses.

Prompt:
"If a customer previously asked about shoe availability, reply: 'You were checking on those running shoes earlier — they’re now back in stock in your size!'"
| Platform | Output                                                                                                 | Analysis                                     |
| -------- | ------------------------------------------------------------------------------------------------------ | -------------------------------------------- |
| ChatGPT  | “Great news! The running shoes you were interested in earlier are now available in your size.”         | Good memory-based reference. Friendly tone.  |
| Claude   | “Remember those running shoes you asked about? They’re now restocked in your size. Want to grab them?” | Informal and engaging. Reflects memory well. |


✅ Evaluation:

Context Awareness: Strong
Tone: Claude slightly more informal and natural
User Experience: High personalization increases conversion

### 3. Persona-Based Prompting
Objective: Create a friendly and relatable chatbot persona.

Prompt:
"Pretend you’re a bubbly store assistant. Respond: 'Hi! I’m here to help you find the perfect outfit today!'"
| Platform | Output                                                                                       | Analysis                        |
| -------- | -------------------------------------------------------------------------------------------- | ------------------------------- |
| ChatGPT  | “Hi there! I’m your style buddy today — let’s find you something amazing!”                   | Persona clear and enthusiastic. |
| Claude   | “Hey hey! Looking to freshen up your wardrobe? I’m your fashion friend – let’s get started!” | High energy and very engaging.  |



✅ Evaluation:

Persona Accuracy: Excellent
Tone: Claude had more flair
Engagement: High emotional resonance in both

### 4. Few-Shot Prompting
Objective: Train with examples and test new input.

Prompt with Examples:
“Examples:
Q: 'Can I return a product bought on sale?'
A: 'Yes, sale items can be returned within 7 days with a receipt.'
Q: 'Do you offer gift wrapping?'
A: 'Yes, we provide free gift wrapping on request.'

Now answer: 'Is there any student discount?'”

| Platform | Output                                                                                 | Analysis                                        |
| -------- | -------------------------------------------------------------------------------------- | ----------------------------------------------- |
| ChatGPT  | “Yes, students get a 10% discount with valid ID. Want help applying it to your order?” | Follows the example pattern perfectly.          |
| Claude   | “Absolutely! Show your student ID at checkout for 10% off.”                            | Friendly and concise. Well aligned with format. |

✅ Evaluation:

Pattern Matching: Strong
Clarity: Both platforms respond cleanly
Engagement: Helpful, informative

### 5. Chain-of-Thought Prompting
Objective: Guide step-by-step troubleshooting.

Prompt:
"When a customer says, 'I bought a blender and it’s not working,' respond by:
Apologizing

Asking for receipt/order ID

Providing troubleshooting or exchange info"

| Platform | Output                                                                                                                                                           | Analysis                             |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ |
| ChatGPT  | “I’m really sorry to hear that your blender isn’t working. Could you please share your order ID? I’ll check the issue and guide you through an exchange or fix.” | Logical and clear. Covers all steps. |
| Claude   | “Oh no! That’s not what we want. Can you share your receipt or order number? We’ll look into a fix or replacement right away.”                                   | Empathetic and structured.           |


✅ Evaluation:

Completeness: All steps covered
Empathy: Claude uses more emotional expressions
Clarity: Excellent

### 6. Instruction with Constraints
Objective: Keep responses short, simple, and clear.

Prompt:
“Use <30 words, simple language: 'Can I cancel my order?' → 'Yes, your order can be canceled within 2 hours. Just click "Cancel Order" in your profile.'”

| Platform | Output                                                                                        | Analysis                             |
| -------- | --------------------------------------------------------------------------------------------- | ------------------------------------ |
| ChatGPT  | “Yes, you can cancel your order within 2 hours. Go to your profile and click ‘Cancel Order.’” | Clear and concise.                   |
| Claude   | “Sure! You can cancel your order in 2 hours. Just visit your profile and hit ‘Cancel.’”       | Simpler wording, easy to understand. |


✅ Evaluation:

Constraint Compliance: Both <30 words
Simplicity: Claude used more natural phrasing
Usability: High for both

### 7. Reflective Prompting
Objective: Mirror user intent to confirm issue before resolving.

Prompt:
"If a user says, 'I didn’t receive my invoice', reply with: 'So you haven’t received your invoice, right? Let me email it to you now.'"
| Platform | Output                                                                                     | Analysis                    |
| -------- | ------------------------------------------------------------------------------------------ | --------------------------- |
| ChatGPT  | “You’re saying the invoice hasn’t reached you yet, correct? I’ll send it over right away.” | Mirrors and clarifies well. |
| Claude   | “You didn’t get your invoice, right? I’ll email it to you now.”                            | Shorter and more direct.    |




✅ Evaluation:

Reflection Accuracy: Good in both
Tone: ChatGPT is slightly more formal
Resolution Action: Clearly provided

## RESULT: Prompt Performance Summary
| Prompt Type                  | Best Performing Platform | Summary of Findings                                     |
| ---------------------------- | ------------------------ | ------------------------------------------------------- |
| Direct Instruction           | both ChatGpt and   Claude                     | Both were clear and helpful                             |
| Contextual Prompting         | Claude                   | More personalized and natural                           |
| Persona-Based Prompting      | Claude                   | Stronger persona and emotional tone                     |
| Few-Shot Prompting           |both ChatGpt and   Claude                       | Both understood pattern and generated accurate response |
| Chain-of-Thought Prompting   | ChatGPT                  | Better structured logical flow                          |
| Instruction with Constraints | Claude                   | Simpler and more user-friendly                          |
| Reflective Prompting         | ChatGPT                  | Better reflection and confirmation of issue             |

## INSIGHTS
ChatGPT excelled at logical problem-solving and formal tone.

Claude provided more emotional depth, especially in persona and empathetic interactions.

Both were highly effective in providing fast, accurate, and customer-friendly support in retail scenarios.

## CONCLUSION
Diverse prompting techniques enhance chatbot responsiveness and user experience in retail. By combining different styles such as direct instructions, emotional tone, step-by-step logic, and context-awareness, AI chatbots can significantly improve customer satisfaction, reduce response time, and drive sales conversions. 
