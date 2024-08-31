# AI-Assisted Predictive Maintenance and Monitoring System (PMMS) for Rooftop Solar PV

Welcome to the official repository for the AI-Assisted Predictive Maintenance and Monitoring System (PMMS) for Rooftop Solar PV. This project aims to enhance the reliability, efficiency, and sustainability of rooftop solar PV systems through advanced AI-driven monitoring and predictive maintenance.

## Repositories

This organization hosts two main repositories:

1. **Client Repository**: [PMMS-Client](https://github.com/PV-monitoring/Client)
2. **Server Repository**: [PMMS-Server](https://github.com/PV-monitoring/Server)

### PMMS-Client
The client repository contains the web application that visualizes the predicted outputs of our AI algorithms. This includes:
- Real-time status monitoring of solar PV systems.
- Visualization of predicted faults.
- Insights into the operational metrics and efficiency of specific PV sites.
- Recommendations for the optimal cleaning cycle based on historical data.

#### Key Features
- **Real-Time Monitoring**: Displays current operational status and performance metrics.
- **Fault Visualization**: Highlights predicted faults before they occur, allowing proactive maintenance.
- **Performance Comparison**: Compares actual generation metrics with expected values based on real-time irradiance levels.
- **Optimal Cleaning Recommendations**: Provides data-driven suggestions for the best times to clean solar panels.

### PMMS-Server
The server repository contains the backend services that support the client application. This includes:
- Data processing and storage.
- Implementation of AI models (LSTM for fault prediction, SOM for condition monitoring).
- APIs for data retrieval and real-time updates.
- Algorithms for determining the optimal cleaning cycle.

#### Key Features
- **Data Management**: Efficiently handles real-time data from solar PV installations.
- **AI-Driven Predictions**: Utilizes advanced AI models to predict faults and monitor conditions.
- **API Services**: Provides RESTful API endpoints for client-side integration.
- **Scalability**: Built to scale with the growing demand for rooftop solar PV systems.

## Getting Started

### Prerequisites
Before you start, ensure you have the following installed:
- **Node.js** (for client-side development)
- **Python** (for server-side AI model execution)
- **Docker** (optional, for containerized deployment)

### Installation

#### Clone the Repositories
```bash
git clone https://github.com/PV-monitoring/Client.git
git clone https://github.com/PV-monitoring/Server.git
