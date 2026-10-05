# AI Travel Planning Agent

An AI-powered travel planning system that generates personalized travel plans based on destination, budget, trip duration, and user preferences.

## Features

- 🤖 Multi-agent AI workflow for travel planning
- ✈️ Flight and transportation research
- 🏨 Hotel and accommodation recommendations
- 🌤️ Weather information
- 🗺️ Personalized itinerary generation
- 💰 Budget-aware travel planning
- 💬 Natural-language travel requests
- 💾 Persistent travel planning sessions

## System Architecture

The system uses multiple specialized agents that work together to create a complete travel plan.

```text
User Request
     ↓
Travel Planning Agent
     ↓
┌──────────────┬──────────────┬──────────────┐
│ Flight Agent │ Hotel Agent  │ Weather Agent│
└──────────────┴──────────────┴──────────────┘
                    ↓
             Itinerary Planning
                    ↓
              Budget Analysis
                    ↓
             Final Travel Plan
