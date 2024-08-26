# Ice Breaker LLM

A repository for learning LangChain🦜🔗 by building a generative AI application.

## Overview

**Ice Breaker LLM** is a web application designed to create personalized ice-breakers by crawling LinkedIn and Twitter data about a person. It uses LangChain to integrate data and generate engaging, context-aware content, making it perfect for networking or social interactions.

## Features

- **Data Crawling:** Fetches information from LinkedIn & Twitter.
- **AI-Generated Content:** Uses OpenAI's API to customize ice-breaker messages.
- **Web Application:** Built using Flask for easy deployment and use.

## Environment Variables

To run this project, you'll need to configure the following environment variables in your `.env` file:

```plaintext
PYTHONPATH=/{YOUR_PATH_TO_PROJECT}/ice_breaker
OPENAI_API_KEY
PROXYCURL_API_KEY
TAVILY_API_KEY
TWITTER_API_KEY
TWITTER_API_SECRET
TWITTER_ACCESS_TOKEN
TWITTER_ACCESS_SECRET
