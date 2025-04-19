# Kemo
 Network Monitor

A comprehensive AI-powered network monitoring system for security threat detection and device tracking.

## Features

- Real-time packet capture and analysis
- Network device discovery and monitoring
- Threat detection using pattern recognition
- AI-based anomaly detection
- Detailed logging and reporting

## Requirements

- Python 3.8 or higher
- Root/Administrator privileges (for packet capture)
- Network interface in monitor mode (for wireless networks)

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/network_monitor.git
cd network_monitor

# Install the package
pip install -e .
```

## Usage

Run the monitoring system:

```bash
# Basic usage (requires root privileges)
sudo network-monitor

# Specify network interface
sudo network-monitor -i eth0

# Specify output directory for logs and data
sudo network-monitor -o /path/to/data/directory

# Set logging level
sudo network-monitor --log-level DEBUG
```

## Configuration

The system can be configured by modifying the settings in the configuration file or through command-line arguments.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

