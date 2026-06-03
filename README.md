# N8N AI-Powered Dropshipping Automation Platform

An intelligent e-commerce automation platform built with n8n, MongoDB, Telegram, Groq LLM, and AI Agents.

The system acts as a virtual sales and support representative that can understand customer intent, manage orders, track shipments, maintain customer memory, and automate customer interactions through Telegram and web chat channels.

---

## Workflow Architecture

### Customer Interaction Flow

```text
Telegram Trigger
       ↓
Normalize Input
       ↓
Detect Intent
       ↓
Intent Routing
(Create / Update / Delete / Status)
       ↓
AI Agent
       ↓
MongoDB Memory
       ↓
Groq LLM Processing
       ↓
Response Formatter
       ↓
Telegram Reply
```

The workflow automatically identifies customer requests and routes them to the appropriate business logic before generating a response.

---

## Core Features

### AI Sales Assistant

The AI Agent can:

* Browse products
* Search products
* Recommend products
* Create orders
* Update orders
* Cancel orders
* Track shipments
* Answer product questions
* Apply coupons
* Handle customer support requests

---

### Smart Intent Detection

The platform automatically classifies customer messages into actions such as:

* Order Creation
* Order Updates
* Order Cancellation
* Shipment Tracking
* Product Search
* General Support

This eliminates the need for manual menu navigation.

---

### Customer Memory System

Powered by MongoDB memory storage.

The system remembers:

* Customer profile information
* Delivery addresses
* Phone numbers
* Preferred payment methods
* Previous conversations
* Order history

This reduces repetitive questions and improves customer experience.

---

### Multi-Order Management

Customers can place unlimited orders.

Features include:

* Unique Order ID per order
* Independent order tracking
* Independent order updates
* Independent order cancellation
* Safe order verification
* Multi-order customer support

The system prevents accidental cancellation or modification of multiple orders.

---

### Automated Customer Support

The AI Agent handles:

* Product inquiries
* Order status checks
* Shipping updates
* Payment questions
* Coupon validation
* General customer assistance

24/7 without human intervention.

---

## Workflow Components

### Telegram Trigger

Receives incoming customer messages directly from Telegram.

### Normalize Input

Standardizes incoming customer data before processing.

### Detect Intent

Identifies customer goals and extracts:

* Product names
* Quantities
* Order references
* Customer actions

### Intent Routing

Routes requests to:

* Create Order
* Update Order
* Delete Order
* Status Check

### AI Agent

Central orchestration layer responsible for:

* Customer conversations
* Decision making
* Business logic execution
* Response generation

### MongoDB Chat Memory

Stores:

* Conversation history
* Customer preferences
* Customer profiles
* Context memory

### Groq LLM

Provides high-speed AI reasoning and natural language understanding.

### Response Formatter

Converts AI outputs into customer-friendly messages.

### Telegram Reply

Sends finalized responses back to customers.

---

## Database Collections

### customers

Stores:

* Customer profiles
* Contact information
* Addresses
* Preferences

### cart

Stores active shopping carts.

### orders

Stores:

* Order details
* Order status
* Order history
* Unique Order IDs

### payments

Stores payment transactions and payment methods.

### shipments

Stores shipment and tracking information.

### categories

Stores product categories.

### coupons

Stores discount and promotional coupon information.

### conversations

Stores customer chat history.

### workflow_logs

Stores execution logs and workflow monitoring data.

---

## Technology Stack

* n8n
* MongoDB
* Telegram Bot API
* Groq LLM
* AI Agents
* JavaScript
* Webhooks
* REST APIs

---

## Key Benefits

* Fully automated customer support
* AI-powered order management
* Persistent customer memory
* Multi-order handling
* Shipment tracking automation
* Scalable workflow architecture
* Reduced operational workload
* Faster customer response times

---

## Use Cases

* Dropshipping Businesses
* E-commerce Stores
* Telegram Commerce Bots
* AI Customer Support Systems
* Automated Order Management Platforms

---

## Project Goal

To create a scalable AI-driven commerce platform capable of managing customer interactions, orders, payments, and shipment workflows through intelligent automation while maintaining a seamless customer experience.


## Telegram Commerce Manager

The platform is powered by the Telegram bot **@dropshipping2026_bot**, which serves as the primary customer-facing interface for order management, product discovery, and AI-powered customer support.

### Bot Features

* Product browsing and recommendations
* AI-powered customer assistance
* Order creation and management
* Shipment tracking
* Coupon validation
* Payment support
* Customer profile management
* Conversation memory
* 24/7 automated support

### Access the Bot

👉 https://t.me/dropshipping2026_bot

The Telegram bot is fully integrated with the n8n automation workflow, MongoDB memory layer, AI Agents, and Groq LLM, enabling intelligent customer interactions and automated e-commerce operations.
