# HavenHosting (HH)

A comprehensive Minecraft hosting platform with anti-DDoS protection, automated server deployment, and integrated payment system.

## Features

- 🚀 **Instant Server Deployment** - One-click Minecraft server setup
- 🛡️ **Enterprise DDoS Protection** - TCP Shield + Cloudflare
- 💳 **Multiple Payment Methods** - Stripe, PayPal, GCash, Maya
- 👥 **Separated User & Staff Systems** - Role-based access control
- 📊 **Real-time Monitoring** - Live console, resource usage tracking
- 🔐 **Advanced Security** - JWT, 2FA, IP blacklist, anti-VPN
- ⚡ **High Performance** - NVMe SSD, Ryzen CPUs, 99.99% uptime
- 🎮 **Plugin Management** - Auto installer, one-click modpacks
- 💾 **Automated Backups** - Daily backups with compression
- 24/7 Support & Monitoring

## Tech Stack

### Frontend
- Next.js 14+
- React 18+
- Tailwind CSS
- Framer Motion
- Socket.IO Client

### Backend
- Node.js
- Express.js
- Socket.IO
- JWT Authentication
- PostgreSQL
- Redis

### Infrastructure
- Docker & Docker Compose
- Pterodactyl Panel
- Nginx Reverse Proxy
- Cloudflare Protection
- AWS/Dedicated Servers

## Project Structure

```
havenHosting/
├── client/                 # Next.js frontend
├── server/                 # Express backend
├── database/               # PostgreSQL schemas
├── docker/                 # Docker configurations
├── nginx/                  # Reverse proxy setup
├── websocket/              # Real-time updates
├── scripts/                # Automation scripts
├── monitoring/             # Health checks & logs
└── docs/                   # Documentation
```

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL 14+
- Docker & Docker Compose
- Cloudflare Account
- Payment API Keys (Stripe, PayPal, GCash, Maya)

### Installation

1. Clone the repository
```bash
git clone https://github.com/Yurielvillanueva/HavenHosting.git
cd HavenHosting
```

2. Install dependencies
```bash
# Frontend
cd client && npm install

# Backend
cd ../server && npm install
```

3. Configure environment variables
```bash
cp .env.example .env.local
# Edit .env.local with your credentials
```

4. Start development
```bash
# Terminal 1: Backend
cd server && npm run dev

# Terminal 2: Frontend
cd client && npm run dev
```

## Pricing Plans

### Starter
- 2GB RAM | 1 vCPU | 10GB SSD
- Basic DDoS | Daily Backups
- ₱99/month

### Advanced
- 6GB RAM | Ryzen CPU | 40GB NVMe
- Premium DDoS | Instant Setup
- ₱299/month

### Extreme
- 16GB RAM | Dedicated Ryzen | 100GB NVMe
- Enterprise DDoS | Unlimited Backups
- ₱799/month

## Security Features

✓ TCP Shield Protection
✓ IP Blacklist/Whitelist
✓ Geo Blocking
✓ Anti-VPN Detection
✓ Login Rate Limiting
✓ Anti-Bot Protection
✓ JWT Authentication
✓ 2FA Security
✓ API Token Validation
✓ Automatic IP Bans
✓ Request Filtering
✓ Security Logs

## Support

- 📧 Email: support@havenhositing.com
- 💬 Discord: [Join Server]
- 🎫 Support Tickets: Dashboard
- 📱 24/7 Customer Support

## License

MIT License - See LICENSE file for details

## Contributing

Contributions are welcome! Please read CONTRIBUTING.md first.

---

**HavenHosting** - Premium Minecraft Hosting Made Simple ✨
