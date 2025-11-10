# Lost Package Chatbot

### Setup Instructions
Use this link to access the Precious Cargo Chatbot: https://dianayousefnejad.github.io/LostPackageChatBot/chatbot.html

### My Approach

For this project, I chose to build a chatbot designed to help customers track a lost package. The chatbot includes two main user flows: checking an order status and reporting a missing/not delivered package. In both flows, the user is asked to provide either their order number or their email address. (An email option is provided as an alternative if the user doesn’t have their order number on hand.)

Order Status Route:
When the user enters their order number or email, the chatbot retrieves their order details and displays the current status.

“I Haven’t Received My Package” Route:
If the user reports that they never received a package, the chatbot also checks the order details. If the order shows as “delivered” but the user still claims non-receipt, the bot informs them that a support representative will contact them within 24 hours and that a claim has been created.

The bot also handles user errors gracefully, including invalid order number formats, non-existent order numbers, and cases where an email doesn’t match any orders.

### Screenshots/Examples of the different coversation paths
