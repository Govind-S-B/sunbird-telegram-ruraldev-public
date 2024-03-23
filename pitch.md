# Utpaad: Facilitating Local Circular Economies for Sustainability through Open Digital Infrastructure

## Problem Statement
- Rural Indian users lack accessible digital interfaces to connect with local consumers quickly.
- Learning new websites and tools is challenging for them.
- Whatsapp is widely used and familiar to them, particularly in regional languages and voice-based communication.
- Promoting local produce and consumption is crucial for sustainable development.
- Centralized commerce platforms may not be accessible to all stakeholders and lack interoperability.

## Solution Overview
- *Utilizing Familiar Interfaces:* Enable buyers and sellers to interact with the Open Network for Digital Commerce (ONDC) through familiar platforms like WhatsApp, leveraging regional languages and voice-based communication.
- *Open Source Tools Integration:* Implement Sunbird Anuvaad Translator, Sunbird Vakyansh Transcriber, Mixtral 8x7B open source AI Model, and ONIX for network setup to facilitate seamless interaction with ONDC.
- *User Interaction Workflow:*
  - Users engage with a bot via voice in their regional language.
  - Speech is transcribed using Sunbird Vakyansh Transcriber and translated to English with Sunbird Anuvaad Translator.
  - Structured data extraction, including items and quantities, is performed using an open-source LLM.
  - Queries are made to the ONDC network to find sellers with the desired items, and users select preferred sellers.
  - Orders are placed via WhatsApp for fulfillment.
- *Seller Inventory Management:* Sellers can add their inventory using natural language, following a similar workflow for data extraction and network database integration.
- *Target Users:* Rural farmers seeking to sell produce locally and consumers looking for local deals easily.
- *User Flow:* Detailed chat window or video demonstration showcasing the interaction between buyers and sellers via a Telegram bot.

## Technologies Utilized
- *Sunbird Anuvaad Translator:* Translation tool for converting regional languages to English.
- *Sunbird Vakyansh Transcriber:* Speech-to-text tool for transcription.
- *Mixtral 8x7B open source AI Model:* Open-source language model for structured data extraction.
- *ONIX:* Network setup tool for connecting with ONDC.

## Benefits
- *Enhanced Accessibility:* Leveraging familiar platforms and regional languages reduces user friction and promotes inclusivity.
- *Promotion of Local Economies:* Facilitating local produce and consumption drives sustainable development and community growth.
- *Equality in Opportunity:* Utilizing ONDC promotes equal access to opportunities for all stakeholders and enables future expansion and interoperability.
