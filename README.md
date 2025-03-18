# CS731_Project_Hyperledger
This project is based on online booking system for Air, Rail and Road travel using Blockchain technology.
The project will be implemented in following manner:
1. System Design Overview
Blockchain Framework: IBM Hyperledger Fabric (private, permissioned blockchain)
Entities:
Users (Passengers): Book/cancel tickets, view travel options.
Service Providers: List transport options, update prices, manage bookings.
Core Features:
Book, cancel, and modify tickets.
Display available transport options with dynamic pricing.
Prevent overbooking and double bookings.
Use blockchain ledger for transaction verification.
Implement a dummy payment system.
Security:
Data privacy between customers and service providers.
Verified transactions through blockchain consensus.
3. Technology Stack
Backend: Node.js, Golang (for smart contracts/chaincode)
Frontend: React.js / Angular (user interface)
Blockchain: IBM Hyperledger Fabric
Database: CouchDB / LevelDB (for off-chain data)
Cloud Deployment (Bonus Marks): AWS / Google Cloud (optional)
4. Development Roadmap
Phase 1: Setup Hyperledger Fabric
Install Docker, Node.js, Golang, Hyperledger Fabric.
Configure peers, orderers, channels for transaction flow.
Implement Chaincode for ticket booking logic.
Phase 2: Implement Functional Features
User Registration/Login (Customers, Service Providers)
Booking System:
List transport options
Book tickets (ledger entry)
Cancel/modify bookings
Pricing & Sorting System:
Sort by ratings, price, transport type
Implement dynamic pricing
Verification System:
Confirm bookings once ledger updates
Prevent duplicate bookings
Blockchain-based identity verification
Phase 3: UI & Web Platform
Build a user-friendly web UI.
Implement REST APIs for frontend-backend communication.
Display available tickets, booking history, and payment status.
Phase 4: Testing & Deployment
Test with 1000+ simulated daily users.
Deploy on cloud servers (AWS, GCP, or Azure).
