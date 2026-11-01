# Pinecity Commutes – WhatsApp Bot

Cloud-API-only bot (no personal chats are read). Deploy steps are in the chat reply; quick local run:

    cp .env.example .env   # fill values
    npm install
    npm start              # creates tables automatically from schema.sql

Webhook URL: https://YOUR-DOMAIN/webhook   Verify token: value of META_VERIFY_TOKEN
Subscribe the webhook to the "messages" field.
