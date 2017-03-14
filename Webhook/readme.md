
webhook v1 using Flask framework

requirement to connect:

The header must be “Content-type: application/json”.
To send formatted messages to bots, use the following format for the "data" field: "data": {"telegram": {<telegram_message>}}

Flowchart

Telegram send JSON ---> Webhook ---> API.AI execute JSON and return JSON result