# Home Automation Simulation - Interactive Smart Home Control

## Use Case
This simulation targets users exploring smart home automation—homeowners, tech enthusiasts, or students—allowing them to control a virtual home and monitor resource usage via chat.

## Problem
Testing real home automation requires expensive hardware and setup. Users lack a simple, interactive platform to simulate controlling devices (lights, HVAC, locks) and tracking energy/water usage.

## Solution
A Jupyter notebook with an LLM-powered chat interface to:
- Control simulated devices (lights, security, TVs, HVAC, locks).
- Track energy (kWh) and water (gal) usage.
- Update a virtual home state based on user commands.
- Provide feedback on actions and current state, including status queries.

## How to Use
1. Run in Jupyter/Kaggle with `langchain-google-genai` installed.
2. Enter commands (e.g., "Turn on kitchen lights") or queries (e.g., "Are all lights off?") in the chat.
3. View responses and updated home state (e.g., "Lights on, Energy: 0.1 kWh" or "Yes, all lights are off").
4. Type "exit" for a final usage summary.
