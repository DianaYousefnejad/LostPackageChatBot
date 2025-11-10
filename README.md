# Lost Package Chatbot

### Setup Instructions
Use this link to access the Precious Cargo Chatbot: https://dianayousefnejad.github.io/LostPackageChatBot/chatbot.html

#### For Testing:

Valid Order Numbers: 

ORD12345 (Shipped)  (john@example.com)

ORD98765 (Delivered) (john@example.com)

ORD55544 (Processing) (sarah@example.com)

Valid Emails:

john@example.com

sarah@example.com 

#### For testing "I haven't received my package" use ORD98765 because it is a delivered package so you can test the "lost package" functionality. 

### My Approach

For this project, I chose to build a chatbot designed to help customers track a lost package. The chatbot includes two main user flows: checking an order status and reporting a missing/not delivered package. In both flows, the user is asked to provide either their order number or their email address. (An email option is provided as an alternative if the user doesn’t have their order number on hand.)

Order Status Route:
When the user enters their order number or email, the chatbot retrieves their order details and displays the current status.

“I Haven’t Received My Package” Route:
If the user reports that they never received a package, the chatbot also checks the order details. If the order shows as “delivered” but the user still claims non-receipt, the bot informs them that a support representative will contact them within 24 hours and that a claim has been created.

The bot also handles user errors gracefully, including invalid order number formats, non-existent order numbers, and cases where an email doesn’t match any orders.
#### Conversation Flow Chart

<img width="1920" height="1080" alt="Heading 1 (1)" src="https://github.com/user-attachments/assets/1c0726da-3573-49e8-bda2-76429b796677" />


### Screenshots/Examples of the different coversation paths

#### Main Menu:

<img width="1212" height="644" alt="Screenshot 2025-11-10 at 10 32 32 AM" src="https://github.com/user-attachments/assets/8484efb8-61e4-4f3c-a2d6-44a3388eb901" />

#### Order Status Route:

<img width="650" height="650" alt="Screenshot 2025-11-10 at 11 23 28 AM" src="https://github.com/user-attachments/assets/b113cb8e-007e-48fe-9eef-61c05428e9e6" />



#### Is there anything else I can help you with:

<img width="650" height="450" alt="Screenshot 2025-11-10 at 10 33 22 AM" src="https://github.com/user-attachments/assets/7a8f4c1d-f3c0-44ba-88f5-d3429d42cfa6" />

#### “I Haven’t Received My Package” Route:

<img width="650" height="650" alt="Screenshot 2025-11-10 at 10 33 59 AM" src="https://github.com/user-attachments/assets/d2022032-b653-473d-9bfe-e51fb8259f49" />


<img width="650" height="650" alt="Screenshot 2025-11-10 at 10 34 17 AM" src="https://github.com/user-attachments/assets/aae1f961-7ada-4ce6-a394-507021b56ea9" />


<img width="650" height="650" alt="Screenshot 2025-11-10 at 11 11 12 AM" src="https://github.com/user-attachments/assets/8737cc41-1675-4efc-ac16-169c40bce7e5" />

### Email route

<img width="650" height="650" alt="Screenshot 2025-11-10 at 11 25 12 AM" src="https://github.com/user-attachments/assets/4e009aa8-e74d-49d5-9520-e4ec0ba545b4" />

<img width="650" height="650" alt="Screenshot 2025-11-10 at 11 25 18 AM" src="https://github.com/user-attachments/assets/3e1cd8d8-f404-45d5-92b4-4b9918438148" />



### Error Handling Examples

#### No valid order number and no valid email:

<img width="650" height="650" alt="Screenshot 2025-11-10 at 11 13 13 AM" src="https://github.com/user-attachments/assets/f0ee91c7-006a-43a5-a2d6-8af0b9e0583b" />

<img width="650" height="650" alt="Screenshot 2025-11-10 at 11 13 32 AM" src="https://github.com/user-attachments/assets/246232e5-8c82-4ba9-80a1-78ef2398f591" />


#### Invalid order number format:

<img width="650" height="650" alt="Screenshot 2025-11-10 at 11 19 02 AM" src="https://github.com/user-attachments/assets/2b5541ef-28c6-426c-a57b-18839d5e3cd1" />


#### Invalid email format:

<img width="650" height="650" alt="Screenshot 2025-11-10 at 2 01 54 PM" src="https://github.com/user-attachments/assets/4ea53fed-9b66-43f8-8726-78924207a277" />


