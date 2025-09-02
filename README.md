
# Welrok Climate Integration for Home Assistant

This integration allows Home Assistant users to control and monitor Welrok thermostats.

## The author of the integration
https://github.com/ishikht/ha-terneo-integration

## Features

- Control HVAC modes (Heat/Off).
- Monitor and set target temperatures.
- View the current temperature of the device.
- Supports multiple devices under one account.

## Installation

### Manual

1. Clone or download this repository.
2. Copy the `terneo` folder to your `custom_components` folder in your Home Assistant configuration directory.
3. Restart Home Assistant.

## Configuration

After installation:

1. Navigate to Configuration > Integrations in the Home Assistant UI.
2. Click on the "+" button to add a new integration.
3. Search for "Terneo Climate" and select it.
4. Provide your Welrok account credentials.
5. Upon successful authentication, your Welrok devices will be added to Home Assistant.

## Troubleshooting

If you encounter issues:

1. Ensure all Welrok devices are online and accessible via the official Welrok app.
2. Check the Home Assistant logs for any error messages related to the Terneo integration.
3. Ensure each device has a unique serial number.

## Contributing

Contributions are welcome! Please submit pull requests against the `dev` branch.

## Disclaimer

This integration is not affiliated with or endorsed by Welrok. Use at your own risk.
