# TRUSTRA 1.0 - Algorithmic Trading Platform

A production-grade algorithmic trading platform with real broker integration, professional bot algorithms, and enterprise-level security.

## Features
- ✅ Real money trading (cTrader, MetaTrader 5, Binance)
- ✅ Professional bot algorithms (Trend, Mean Reversion, Breakout)
- ✅ PostgreSQL database with full transaction support
- ✅ Risk management & position management
- ✅ Argon2id password hashing + JWT authentication
- ✅ Complete audit logging
- ✅ Docker deployment ready

## Quick Start

### Prerequisites
- Python 3.11+
- PostgreSQL 14+
- Redis 7+
- Docker & Docker Compose (optional)

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/trustra.git
cd trustra

cp .env.example .env
# Edit .env with your configuration
pip install -r requirements.txtpsql -U trustra_user -d trustra_db -f init_database.sqldocker-compose up -d
