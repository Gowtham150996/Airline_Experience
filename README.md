# Airline Experience Feedback App

## Overview

The Airline Experience Feedback App is an AI-driven solution for handling customer feedback in the airline industry. 
It leverages LangChain for decision-making and StreamLit for the user interface to analyze user reviews and provide 
instant, contextually appropriate responses.

The app classifies feedback into three categories:
1. Positive experiences
2. Negative experiences caused by the airline
3. Negative experiences caused by external factors

Each feedback category is addressed with a tailored response to ensure professional and empathetic customer service.

## Features

- Interactive user interface for feedback collection.
- AI-powered classification of feedback using LangChain.
- Automated, contextually appropriate responses.
- Scalable design suitable for various industries.
- Professional tone and empathetic handling of feedback.

## Architecture

The app uses LangChain for decision-making and routing logic, combined with StreamLit for the frontend. 
User reviews are classified using predefined prompts and routed to specific response chains based on their classification:
- Positive Feedback: Thanks the user.
- Negative Feedback (Airline’s Fault): Offers sympathies and ensures follow-up.
- Negative Feedback (External Factors): Offers sympathies and explains non-liability.

The architecture integrates StreamLit, LangChain, and OpenAI GPT models to deliver a seamless experience.

## Prerequisites

- Python 3.8 or later
- OpenAI API Key
- StreamLit

## Installation

Clone the repository:
   ```bash
   git clone https://github.com/Airline_Experience/airline-feedback-app.git
   cd airline-feedback-app

