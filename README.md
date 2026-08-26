# SIH-Prototype

# (Net Realizable Value Engine)
Smart India Hackathon 2026 Prototype

## 🚨 The Problem
Farmers often make selling decisions based on the highest Gross Mandi Price. However, this is a trap. Chasing a price that is ₹2/kg higher at a market 50km away often results in a net loss due to transportation costs, APMC taxes, and transit spoilage. 

## 💡 The Solution
KisanSetu-NRV flips the model. Instead of gross price, we calculate the Net Realizable Value (NRV) — the actual money that goes into the farmer's pocket. 

We deliver this intelligence directly to the farmer's phone via a lightweight, accessible Telegram Bot, requiring zero app installations or technical literacy.

## ⚙️ Core Features (Hackathon Scope)
1. NRV Buyer Discovery Engine: Vectorized Pandas engine that computes freight costs, APMC taxes, and quintal-conversions to rank buyers by actual profit, not gross price.
2. Conversational Interface: Telegram Bot API integration for immediate, low-barrier farmer access.
3. Market Intelligence (WIP): Time-series forecasting for price trend analysis.
4. Spatial Micro-Pooling (WIP): Haversine distance-based clustering for optimized logistics.

## 🛠 Tech Stack
* Language: Python
* Data Processing: Pandas (Vectorized operations)
* Interface: Telegram Bot API
* Environment: Google Colab (Cloud execution)

