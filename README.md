# rssAggregator

This is a backend server application built in Go that efficiently fetches, aggregates, and serves content from various RSS feeds. It utilizes PostgreSQL for data storage and provides secure API key-based authentication for controlled access.

## 🚀 Features

- Fetches and aggregates content from multiple RSS feeds.
- Secure user authentication using API keys.
- Subscription management for users to manage their following feeds.
- Background tasks for scheduled feed updates.
- Optimized PostgreSQL schema for data storage.
- Error handling and logging mechanisms for enhanced robustness.

## Getting Started

These instructions will help you set up and run the RSS Aggregator on your local machine for development and testing purposes.

### Prerequisites

- Go (Golang) installed
- Docker (optional, for deployment)

### Installation Guide

1. Clone the repository:
   ```sh
   git clone https://github.com/eugenetye/rssAggregator.git
   cd rssAggregator

2. Install dependencies:
   ```sh
   go get -v ./...
3. Build and run the server:
   ```sh
   go build && ./rssAggregator
4. Access the server at http://localhost:8080.
