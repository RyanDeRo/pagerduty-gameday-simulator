# PagerDuty GameDay Simulator

A web-based training tool for running realistic PagerDuty incident response exercises.

## Features

- **Tier 1 Training**: Basic responder tasks (profile setup, schedules, incident response)
- **Tier 2 Training**: Manager configuration tasks (escalation policies, event orchestration)
- **Event Simulator**: Generate and send realistic PagerDuty events via Events API v2

## Usage

1. Open `index.html` in a web browser
2. Review the training instructions for your tier
3. Enter your PagerDuty integration routing key
4. Click "Generate New Payload" to get a random scenario (optional)
5. Edit the JSON payload as needed
6. Click "Create Event" to trigger the incident

## Getting Your Routing Key

1. Log into your PagerDuty account
2. Navigate to **Services** → Select your service
3. Go to the **Integrations** tab
4. Find or create an **Events API v2** integration
5. Copy the **Integration Key** (routing key)

## Hosting

This is a static website that can be hosted on:
- GitHub Pages
- Any web server
- Locally (just open the HTML file)

## Safety

⚠️ **For testing/training purposes only**
- Never commit routing keys to version control
- Routing keys are not stored between sessions
- Use a dedicated test service in PagerDuty

## License

Internal PagerDuty tool - not for public distribution.
