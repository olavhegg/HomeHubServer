# Smart Home Server

Home Assistant based smart home server with custom integrations and API endpoints.

## Components

- Home Assistant Core
- PostgreSQL Database
- MQTT Broker
- Homebridge Integration
- Custom API Integrations

## Directory Structure

```
home-server/
├── config/
│   ├── configuration.yaml    # Main HA config
│   ├── secrets.yaml         # Sensitive data
│   ├── automations.yaml     # Automation rules
│   └── integrations/        # Integration configs
├── custom_components/       # Custom integrations
│   └── api_fetcher/        # External API handler
├── themes/                  # UI themes
├── www/                    # Static files
└── docker/                 # Deployment configs
```

## Features

- Device Control & Monitoring
- External API Integration (Weather, Stocks)
- Custom REST API for iOS Apps
- Homebridge Integration
- Activity & Usage Analytics

## Setup

1. Install Home Assistant
2. Configure PostgreSQL
3. Set up MQTT broker
4. Configure Homebridge integration
5. Add custom components

## Development

Development environment requires:
- Python 3.10+
- PostgreSQL 14+
- MQTT Broker
- Node.js 18+ (for Homebridge)

## API Documentation

Access API documentation at `http://server-ip:8123/api/docs`
