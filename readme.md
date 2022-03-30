

### How to use?
- Run `npm install`
- Run `npm run start:dev`
- Open browser and go to address `http://localhost:8000`
- Scan the QR Code
- Enjoy!

### Send message to group

You can send the message to any group by using `chatID` or group `name`, chatID will used if you specify the `id` field in the form, so if you want to send by `name`, only use name.


**Paramaters:**

- `id` (optional if name given): the chat ID
- `name` (optional): group name
- `message`: the message

Here the endpoint: `/send-group-message`

Here the way to get the groups info (including ID & name):

- Send a message to the API number `!groups`
- The API will replying with the groups info
- Use the ID to send a message
- you can test using Postman Client

