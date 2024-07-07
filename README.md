# k6 Performance Testing Project

This repository contains scripts and configurations for performance testing using k6, as described in the accompanying Medium article, "Testing the Limits: k6 Takes the Load Off Your Shoulders". The project demonstrates how to set up and run performance tests using k6, Docker, Grafana, and InfluxDB, aimed at ensuring your applications can handle high loads efficiently.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- [k6](https://k6.io/docs/getting-started/installation)
- [Docker](https://docs.docker.com/get-docker/)
- Docker Compose (usually installed with Docker)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/k6-performance-testing.git
   cd k6-performance-testing
   
### Running the tests
docker-compose up -d

docker-compose run k6 run /scripts/stress-test.js

### Usage

After running the tests, access the Grafana dashboard at http://localhost:3000/ to view the performance data visualized. InfluxDB can be accessed at http://localhost:8088/.

### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request

### License
Distributed under the MIT License. See LICENSE for more information.

### Contact
v.seena001@gmail.com
