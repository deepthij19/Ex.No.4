# Ex.No.4-EXP 4 Generate the Prompt and eveluate that for following prompt types - Comparative Analysis Prompt Experiential Perspective Prompt - Everyday Functioning Prompts - Universal Prompt Structures Prompt Refinements- Prompt Size Limitations.
### DATE: 3.9.25                                                                           
### REGISTER NUMBER : 212223060041

# Aim:
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 2 with Comparative Analysis Prompt, Universal Prompt, Structures Prompt Refinements and Prompt Size Limitations

Explanation - Any one use case from Unit 5 and generate the report for that with the unit 2 Prompt type

# Procedure:

1. Understanding Chatbot Requirements:
The chatbot must answer customer FAQs, track orders, provide product recommendations, and handle complaints politely.
2. Selection of Prompting Techniques:
We selected a wide range of prompting techniques — including Zero-shot, Few-shot, Chain-of-Thought, Role Prompting, and others — to cover different aspects of chatbot development.
3. Prompt Design:
For each technique, prompts were specifically designed to handle real-world customer scenarios such as order tracking, damaged item reporting, and delayed delivery.
4. Experimentation:
Each prompting technique was applied to the same scenario to evaluate how the chatbot responded.
5. Observation and Analysis:
The quality, tone, and accuracy of the chatbot’s responses were compared to determine which techniques produced the best customer experience.
6. Identify Prompt Patterns for Each Design Aspect:

Idea Generation Prompts:

Prompt: “What features can be incorporated into the automation system to optimize production and reduce downtime?” Generated Ideas:
Sensors for real-time monitoring of equipment performance.
Predictive maintenance alerts to anticipate equipment failures.
Energy usage optimization by automating the switching of machines on/off based on demand.
Cloud-based dashboards for remote monitoring and control of machinery.

Persona and Context Prompts:

Prompt: “What should the user interface and control system convey to the operators and managers?” Generated Context:
The user interface should be intuitive and provide real-time data on machine performance, energy usage, and alerts.
The system should convey reliability and ease of use, with minimal training required for operators.

Main Objectives:
Improve production efficiency by 30%.
Minimize machinery downtime with predictive maintenance.
Enable real-time monitoring and remote control of manufacturing systems.
Reduce energy consumption by optimizing processes.

Prompt Design and Techniques

1. Zero-Shot Prompting
Without giving examples, the chatbot was asked to respond directly to a query.

Prompt: “Where is my order #12345?”
Observation: The chatbot could respond, but tone consistency varied. Sometimes the response was too generic or robotic.

3. One-Shot Prompting
A single example was provided before asking the chatbot to respond to a new query. Prompt Example:
“Example: Customer asks: Where is my order #98765? → Bot: Your order is out for delivery and will arrive tomorrow.
Now answer: Where is my order #12345?”
Observation: The chatbot’s response became more aligned with the expected format and tone.

5. Few-Shot Prompting
Multiple examples were given to set a clear pattern for the chatbot to follow.
Observation: This significantly improved the chatbot’s tone and consistency. It maintained a polite, professional style even for new queries.

7. Chain-of-Thought Prompting
The chatbot was instructed to think step by step before answering. Prompt Example: “The customer says they received a damaged item.

Think step by step:
Apologize,
Ask for details,
Offer a replacement.”

Observation: The responses became well-structured, covering all steps systematically.

7. ReAct Prompting
The chatbot was instructed to reason and then take action.

Prompt Example: “Decide if a refund or replacement is more appropriate. Think first, then respond to the customer.”
Observation: This approach worked best for decision-making tasks like returns and refunds.

6. Self-Consistency Prompting
The chatbot generated multiple possible responses and selected the most appropriate one.
Observation: The final chosen response was usually more balanced and customer friendly.

8. Role Prompting
The chatbot was given a role to play. Prompt Example:
“You are a polite and empathetic customer service agent. Help the customer track their order.”
Observation: This produced highly natural, professional, and empathetic replies.

8. Tree-of-Thought Prompting
The chatbot was encouraged to explore multiple solutions before picking the best one. Prompt Example:
“Generate three ways to resolve a delayed shipment:
 (1) Apologize and offer a discount,
 (2) Offer a replacement,
 (3) Give updated ETA. Choose the best option.”
Observation: The chatbot became more creative and considered customer satisfaction while deciding.

10. Reflection Prompting
The chatbot was asked to review and refine its own response. Prompt Example:
“Here’s your answer: . Make it more polite and professional.”
Observation: The response quality improved significantly, with more polished and customer-friendly wording.

12. Multimodal Prompting
Text and image were combined.
Example: Uploading a product image and asking: “Is this available in blue?”
Observation: Useful for product-related queries but requires an image database
Scenario
Situation:

A customer reports a damaged item and wants a resolution.
We will apply two prompting techniques and compare the outputs.
image
Technique 1: Few-Shot Prompting
Prompt:

Classify and respond to customer complaints in a polite, solution-oriented way.
Example 1:
Customer: My order was late.
Bot: I'm really sorry your order was delayed. I have checked and it will reach you today.
Thank you for your patience!

Example 2:
Customer: I received the wrong item.
Bot: I apologize for the mix-up! I have initiated a replacement request. You will receive the correct item within 3-4 working days.

New Case:
Customer: I received a damaged item. Output:
Bot: I’m very sorry to hear that your product arrived damaged. I have initiated a replacement request at no extra cost.
You will receive the new item within 3-4 working days.
Would you like me to arrange a pickup for the damaged product?

<img width="681" height="625" alt="image" src="https://github.com/user-attachments/assets/25ae1671-960b-43e4-9474-aaed528ae931" />

Observation:
Polite, structured, and aligned with the examples given.
Maintains consistency and professional tone.
Automatically suggests a solution without needing extra clarification.
Technique 2: ReAct Prompting

Prompt:
Customer: I received a damaged item. Reason step by step:
Identify the type of complaint (damaged product).
Decide whether to offer a refund or a replacement (replacement is better for customer satisfaction).
Respond politely and take action.

Output:
Reasoning: The complaint is about a damaged item. Offering a replacement is better than refund because it retains the sale and keeps the customer happy. We should apologize, confirm replacement, and ask for pickup details.
Final Response:

Bot: I’m sorry to hear your item was damaged. I have arranged a replacement for you at no cost.
It will arrive within 3-4 business days. Could you confirm your address for the pickup of the damaged item?
Observation:
Explains reasoning before answering.
Chooses the most customer-friendly action.
Response is empathetic and actionable.

<img width="580" height="519" alt="image" src="https://github.com/user-attachments/assets/8dd5fd6d-fdb2-4ad3-9ef3-d69b731aff1c" />

# Result:
Both techniques improved the chatbot’s response quality compared to a simple zeroshot prompt. For a retail chatbot, combining both techniques would be ideal:
Use Few-Shot Prompting for common FAQs and routine scenarios.
Use ReAct Prompting for complaints, refunds, or complex decision-making where reasoning is essential. Thus the Prompts were executed successfully.
