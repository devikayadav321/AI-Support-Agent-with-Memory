# AI Support Agent with Memory

An intelligent customer support agent powered by Hindsight memory that learns from customer history and provides personalized responses.

## Problem Solved
Customer support teams waste time repeating the same questions. Customers get frustrated when they have to explain their issue again. This agent remembers customer history and delivers personalized help on every interaction.

## How It Works
1. Customer selects themselves from the system
2. They describe their issue
3. The agent retrieves their past interaction history from memory
4. The agent provides personalized support based on what worked before

## Key Features
- **Memory-Powered Responses:** Agent recalls past issues and solutions
- **Personalized Support:** Every response is tailored to customer history
- **Simple UI:** Easy for customers to interact with
- **Real-time Learning:** Agent improves with each interaction

## Why Memory Retrieval is Harder Than It Looks

Initial approach: keyword matching on past tickets. Result—wrong matches. If a customer said "network down" last time and "WiFi broken" this time, the system didn't connect them.

Solution: used semantic similarity (Hindsight) instead of keyword matching. Now similar issues get retrieved even if the language is different.

Trade-off: Hindsight adds latency. Next phase is caching frequently-accessed histories.

## Demo
Select a customer with existing support history, describe an issue, and watch the agent provide personalized help based on their past interactions.

## Built With
- HTML/JavaScript
- Groq API (LLM integration)
- Hindsight Memory System

## Try It
Open `index.html` in your browser to see the demo.
