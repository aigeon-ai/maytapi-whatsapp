# Maytapi WhatsApp MCP Server

Welcome to the **Maytapi WhatsApp MCP Server** README! This document provides an overview of the capabilities and functionalities of the Maytapi WhatsApp server, which enables seamless integration with WhatsApp for message sending and receiving, session management, and account handling.

## Overview

The Maytapi WhatsApp MCP Server is a robust solution designed to facilitate communication via WhatsApp. It allows users to send and receive both text and media messages in private chats. Additionally, it offers functionalities to retrieve session statuses and manage account-specific settings, such as product information and registered phone details.

## Key Features

### Message Operations

- **Send Messages:** Allows the sending of both text and media messages (images, videos, audio, and documents) to specified WhatsApp numbers.
- **Receive Messages:** Automatically handles incoming messages and directs them to a specified webhook for processing.

### Session Management

- **Session Status:** Retrieve detailed information about the current session status, including login state, QR code availability, and connection status.
- **Session Control:** Perform actions such as restarting sessions, backing up session data, and logging out to manage the WhatsApp session effectively.

### Account Management

- **Phone Management:** Add new phones to the account, list registered phones, and manage phone details.
- **Webhook Configuration:** Set and manage webhooks to direct incoming messages and session updates to your desired endpoint.
- **Acknowledgment Preferences:** Configure acknowledgment settings to receive delivery notifications for sent messages.

### Group Chat Operations

- **Create and Manage Groups:** Set options for receiving acknowledgment messages for group chats, ensuring seamless group communication.

### Queue Management

- **Queue Information:** Retrieve information about the message queue for each phone to monitor message dispatch statuses.
- **Clear Queue:** Purge the message queue when necessary to maintain optimal performance.

## Tool List

The following tools are available within the Maytapi WhatsApp MCP Server:

### Session Information Getters
- **Get Status:** Retrieve the current session status.
- **Get QR Code:** Obtain the current QR code for authentication.
- **Get Screen:** Capture a screenshot of the current session screen.
- **Check Number Status:** Verify the status of a phone number.
- **Logs:** Access logs for troubleshooting.
- **Contacts:** Retrieve contacts from the active WhatsApp session.

### Session Controlling Operations
- **Clear:** Reset browser information; requires QR code scanning afterward.
- **Restart:** Refresh the session to resolve issues.
- **Backup:** Save session data for later restoration.
- **Logout:** End the current session and return to the QR code screen.
- **Restore:** Reload a session using backed-up data.
- **Redeploy:** Restart the phone's docker instance for troubleshooting.

### Message Sending Operations
- **Send Message:** Dispatch text or media messages to specified contacts.

### Account Information Retrieval & Edit
- **Get Product:** Access product and webhook information.
- **Get List Phones:** Retrieve a list of registered phones.
- **Set Webhook:** Configure the webhook URL.
- **Set Acknowledgment Preference:** Adjust acknowledgment notifications.
- **Add Phone:** Register a new phone to the account.

### Group Chat Operations
- **Create Group:** Manage acknowledgment settings for group chats.
- **Get Groups:** Retrieve information about existing groups.

### Queue Operations
- **Queue:** Get message queue information.
- **Purge Queue:** Clear the message queue.

This README provides a high-level overview of the features and tools available in the Maytapi WhatsApp MCP Server. For detailed instructions on using each tool, please refer to the server's documentation or contact support for assistance.