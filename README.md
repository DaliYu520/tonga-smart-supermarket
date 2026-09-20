# Tonga Smart Supermarket — V3 Customer Demo

This is a PWA customer-facing prototype for a future supermarket digital operations platform.

## Demo modules
- Dashboard / owner view
- Smart POS: scan / click / search / voice entry
- Orders: store + online/AI draft orders
- Inventory / low-stock / AI replenishment ideas
- Purchasing & suppliers
- AI marketing: promotion copy for Facebook / Messenger / Chinese / English / Tongan
- Customer chat and AI order draft
- Pickup / delivery tracking
- Multilingual voice center: Chinese / English / Tongan test entry
- AI owner analytics

## Important
- Pricing and arithmetic are deterministic app logic; AI is not used to calculate money.
- Voice recognition currently uses the browser SpeechRecognition API where available for demonstration. Tongan (`to-TO`) support varies by browser/device and MUST be field-tested; production can later connect a dedicated AI speech-to-text/translation service.
- Payment, cloud database, real Messenger/Facebook APIs, inventory sync, and production authentication are not connected in this demo.
- The UI and data model are intentionally designed to leave room for later modules without rebuilding the POS from scratch.

## Deployment
This repository is intended for Vercel static deployment. No backend or real customer/payment data is included in this demo.
