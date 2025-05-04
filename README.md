# FLXA Indonesia

## Overview
The FLXA Balance Service provides backend functionalities for:
- Managing user FLXA token balances.
- Handling transactions related to balance updates.
- Integrating with payment gateways for top-ups.
- Interacting with the IOTA Tangle for decentralized balance management.

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