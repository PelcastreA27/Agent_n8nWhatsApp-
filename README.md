# WhatsApp Automation Flow with n8n & Meta Business API

This repository contains the **automation flow built in n8n** to send messages via **WhatsApp Business Cloud API**.  
The project is designed to handle automated messaging, reporting, and integration with Meta’s official API.

---

## Features
- ✅ Send messages to WhatsApp using Meta Cloud API  
- ✅ Dynamic message templates (variables supported)  
- ✅ Test messages with registered recipient numbers  
- ✅ Configurable and reusable n8n workflow  
- ✅ Support for production and local deployment  

---

##  Requirements
- [n8n](https://n8n.io/) installed (locally or hosted, e.g. Railway/Render/Docker)  
- A [Meta for Developers account](https://developers.facebook.com/)  
- A **WhatsApp Business App** created under your Meta account  
- Permanent or test **Access Token**  
- A registered **Phone Number ID** and **Recipient number** in international format (E.164)  

---

## Setup

### 1. Environment Variables
Create a `.env` file in your n8n project and add:

```env
META_ACCESS_TOKEN=your_meta_api_token
PHONE_NUMBER_ID=your_whatsapp_phone_number_id
