# HackOnHills
#  Procurlify — Decentralized Procurement Portal

Procurlifyis a **blockchain-powered procurement and tendering system** designed for transparent, fair, and efficient contract management.  
Admins (e.g., government departments or institutions like colleges) can **create tenders**, manage bids, and automatically select the **lowest bidder** — all while ensuring data integrity through decentralized architecture.

---

##  Features

###  Admin (Local Government Bodies / Institution / Private Companies)
- Create and publish new **tenders** with detailed requirements and deadlines  
- Manage and approve **contractor registrations**  
- **Start / pause / end bidding** windows  
- View all bids and automatically select **lowest valid bid**  
- Audit-ready records of every bid and transaction  

###  Contractor
- **Register** and verify identity (organization details, certifications, etc.)  
- **Connect crypto wallet** (MetaMask, WalletConnect, or Phantom)  
- Browse and **apply to tenders**  
- Submit **bids on-chain**  
- Track bid results and payment status

  ###  Public
  - Even common people can check the transparency of the tenders and how their investment/tax is being used.

###  Blockchain Integration
- **Wallet-based login (Sign-in with Ethereum)** for identity verification  
- **Smart contracts** to store bids and determine winners transparently  
- Immutable audit trail of all procurement actions  

### 🧠 Technology Stack
| Layer | Tech |
|-------|------|
| Frontend | [React.js](https://reactjs.org/), [Tailwind CSS](https://tailwindcss.com/), [Wagmi](https://wagmi.sh/) |
| Backend | [Node.js](https://nodejs.org/), [Prisma ORM](https://www.prisma.io/), [Supabase](https://supabase.com/) |
| Database | PostgreSQL (via Supabase) |
| Blockchain | Ethereum / Polygon (via Ethers.js / Web3.js) |
| Auth | Supabase Auth + Wallet Sign-in (EIP-4361) |


