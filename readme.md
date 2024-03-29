# Telegram Bot for daily Weather Update

I am thrilled to present my latest creation, the Telegram Weather Update Bot. This bot offers an innovative solution for users to stay updated on the weather conditions. With two key commands, it provides a seamless experience for weather enthusiasts.

The first command is "/subscribe [cityname]," which enables users to subscribe to daily weather updates. At 9:00 AM, a cron job, powered by the node-cron package, retrieves active subscriptions from the database. The bot then sends personalized weather updates to each user's chatId, based on their selected city. This functionality is implemented using the node-telegram-bot-api.

The second command, "/weather [cityname]," allows users to instantly retrieve weather details for any city, without the need for a subscription.

You can find the Telegram Bot Handle at t.me/WeatherUpdateASTBot.

To enhance the user experience, I have developed an admin panel. It provides comprehensive features for managing user accounts, including deletion and subscription blocking. Additionally, I have implemented a bot settings area that allows users to easily update their API keys. To handle these tasks, I have created a REST API that fetches data from a MongoDB database, which stores information such as subscribed users and bot settings. The UI part of the admin portal is developed using react.js.

For communication between the Telegram bot and my backend, I have utilized the node-telegram-bot-api library, leveraging the provided API key.

## Tech Stack

**Client:** React.js, Telegram Bot

**Backend** MongoDb, Express and Node.js
#   T e l e g r a m B o t 
 
 
