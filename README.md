# chatbot-assistant

A node.js based Telegram chatbot which provides personalized services that users can subscribe to and get notifications throughout the day. The user's information is being kept in a database and it is used to keep track of the users it needs to broadcast to.

Upon a start request from the client, chat id will be saved and associated with services requested from the client, such as news from supported sites, weather report, etc. sending updates for subscriptions at specific time.

Intreface of the chat bot are short commands (/subscribe , /set , unsubscribe , etc.) starting question sequence to complete the request from the client.

- Telegram Bot Api: https://core.telegram.org/bots/api
