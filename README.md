# FLXA IOTA for Moveathon

## Overview
FLXA is a revolutionary solution set to transform how Indonesians manage their mobile credit—faster, more flexible, and more efficient than ever before. Developed by a team from Universitas Gadjah Mada, Indonesia, this centralized mobile credit wallet empowers users to manage multiple networks with a single top-up. In Indonesia, over 350 million SIM cards are registered, yet only around 160 million are actively used, highlighting the widespread practice of managing multiple SIM cards across various providers. This creates inefficiencies for users, who often juggle credit balances between networks. FLXA addresses this challenge by introducing a unified wallet that allows users to top-up once and seamlessly access any network linked to their registered SIM cards. Whether accessed directly via GSM network services or through a dedicated mobile application, FLXA offers maximum flexibility and ease of use. This innovation simplifies mobile credit management, enhancing user convenience by eliminating the need for separate top-ups for each individual provider. The primary market for FLXA is Indonesians aged 25–35, who frequently switch between multiple SIM cards. A recent survey revealed that 96% of individuals in this demographic are willing to use FLXA, signaling strong market demand. Beyond benefiting users, FLXA also provides significant value to telecommunication providers. It expands their reach, increases top-up volumes, and allows providers to maintain full control over their pricing models, as FLXA does not interfere with pricing decisions. Under the hood, FLXA utilizes a microservice architecture and cutting-edge cloud technology to ensure scalability, reliability, and seamless performance, even with massive traffic. These technologies guarantee high uptime and exceptional scalability, making FLXA a robust platform for mobile credit management. By combining a user-centric design with powerful cloud infrastructure, FLXA is set to revolutionize mobile credit management, offering a smarter, faster, and more efficient way for users to stay connected.

## Services
1. FLXA App: Mobile application to interact with FLXA.
2. FLXA Token: Move Package built to create FLXA Coin which is deployed on IOTA Testnet.
3. User Service: Service to manage our user's personal data.
4. Auth Service: Process user registration, login, and OTP verification.
5. Balance Service: Manage FLXA balance and interact with third-party payment gateways.
6. Card Service: Process SIM card registration and card management.
7. Token Service: Process reward transaction with FLXA Coin.
8. FLXA Provider Web: Additional interface to act as telecommunication service provider.

## Getting Started
### Submodule Initialization

### Installation
1. Clone the repository:
```bash
git clone https://github.com/FLXA-Indonesia/FLXA-IOTA-Moveathon.git
cd FLXA-IOTA-Moveathon
```

2. Update submodules:
```bash
git submodule update --init --recursive
```

3. Install dependencies of each modules. Please follow the initialization instruction in each README files.

## API Endpoints and Testing
You can test the endpoints using Postman with this collection: [FLXA Postman Documentation](https://www.postman.com/winter-desert-840751/flxa-iota).

Note: Authentication middleware ensures that only authorized users can access certain endpoints.

## Contributing
We welcome contributions. To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear messages.
4. Push your branch and open a pull request detailing your modifications.
5. Please ensure your code adheres to the project's coding standards and includes relevant tests.

## License
This project is licensed under the [GNU Affero General Public License V3](LICENSE)
