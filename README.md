# 🏠 Manzil Real Estate Portal

A comprehensive AI-powered real estate platform with CRM integration, agent management, marketing automation, and lead tracking.

## 📋 Project Overview

**Manzil** is a full-featured real estate portal built with modern technologies, designed to streamline property listings, lead management, and agent performance tracking.

### Key Features

#### 🏢 **Agent Management System**
- Agent profiles and performance metrics
- Active listings management
- Lead assignment and tracking
- Performance analytics dashboard

#### 📊 **CRM System**
- Lead capture and qualification
- Lead scoring and tracking
- Source tracking (organic, ads, referrals)
- Pipeline management:
  - New Lead → Contacted → Interested → Site Visit → Negotiation → Booking → Closed Deal

#### 🚀 **Marketing Automation**
- WhatsApp automation and campaigns
- Email campaigns and follow-ups
- Lead nurturing workflows
- Multi-channel marketing

#### 📈 **Integrations**
- GoHighLevel CRM (Primary)
- Meta Lead Ads
- Google Ads & GA4
- Google Tag Manager
- WhatsApp Business API

#### 📱 **Admin & CEO Dashboard**
- Real-time lead analytics
- Conversion rate tracking
- Revenue reports
- Agent performance metrics
- Marketing ROI analysis

## 🛠️ Technology Stack

### Frontend
- **HTML5 / CSS3** - Static pages and responsive design
- **JavaScript** - Client-side interactivity
- **WordPress + Elementor Pro** (optional) - CMS and page builder
- **JetEngine** (optional) - Advanced forms and CRM integration

### Backend
- **Node.js / Express** (recommended) - API server
- **Python** (alternative) - Backend logic

### Database
- **PostgreSQL** - Primary database
- **Redis** - Caching and real-time updates

### Infrastructure
- **Cloudflare** - CDN and security
- **LiteSpeed** - Web server optimization
- **GoHighLevel** - CRM backend

## 📁 Project Structure

```
manzil-real-estate/
├── frontend/
│   ├── index.html              # Main homepage
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── main.js
│   ├── pages/
│   │   ├── properties.html
│   │   ├── agents.html
│   │   ├── dashboard.html
│   │   └── crm.html
│   └── assets/
│       ├── images/
│       └── icons/
├── backend/
│   ├── api/
│   │   ├── routes/
│   │   │   ├── properties.js
│   │   │   ├── agents.js
│   │   │   ├── leads.js
│   │   │   └── users.js
│   │   └── controllers/
│   ├── services/
│   │   ├── crm.js
│   │   ├── lead.js
│   │   └── agent.js
│   ├── integrations/
│   │   ├── gohighlevel.js
│   │   ├── meta.js
│   │   ├── google.js
│   │   └── whatsapp.js
│   ├── automation/
│   │   ├── email.js
│   │   └── whatsapp.js
│   ├── middleware/
│   ├── config/
│   └── server.js
├── database/
│   ├── migrations/
│   ├── seeds/
│   └── schema.sql
├── docs/
│   ├── API.md
│   ├── SETUP.md
│   └── DEPLOYMENT.md
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js 14+
- PostgreSQL 12+
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/raomuzaffarahmad-cmd/manzil-real-estate-.git
cd manzil-real-estate-
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. **Initialize database**
```bash
npm run db:migrate
npm run db:seed
```

5. **Start the development server**
```bash
npm run dev
```

Visit `http://localhost:3000` in your browser.

## 📚 Features Breakdown

### Phase 1: MVP (Weeks 1-4)
- ✅ Agent profiles & management
- ✅ Property listings interface
- ✅ Lead capture forms
- ✅ Basic CRM pipeline
- ✅ GoHighLevel integration
- ✅ Admin dashboard (basic)

### Phase 2: Enhancement (Weeks 5-8)
- ✅ Lead scoring system
- ✅ Agent performance metrics
- ✅ Email automation
- ✅ WhatsApp automation (basic)
- ✅ Meta Lead Ads integration

### Phase 3: Advanced (Weeks 9-12)
- ✅ Advanced lead nurturing
- ✅ Full WhatsApp automation
- ✅ GA4 integration
- ✅ CEO dashboard with advanced analytics
- ✅ Agent portal with real-time updates

## 🔌 API Integration Points

### GoHighLevel CRM
- Lead creation and updates
- Contact synchronization
- Pipeline management

### Meta Lead Ads
- Lead import automation
- Campaign performance tracking

### Google Ads & GA4
- Conversion tracking
- Traffic analytics
- Campaign ROI measurement

### WhatsApp Business API
- Automated messages
- Lead notifications
- Two-way messaging

## 📊 Database Schema

### Core Tables
- `users` - Platform users (buyers, sellers, agents, admin)
- `agents` - Real estate agents
- `properties` - Property listings
- `leads` - Lead records
- `pipeline_stages` - CRM pipeline stages
- `integrations` - API credentials and settings

## 🔐 Security

- JWT authentication
- Password hashing (bcrypt)
- Rate limiting
- Input validation
- SQL injection protection
- CORS configuration

## 📞 Support & Maintenance

- 90 days of post-launch support
- Bug fixes and updates
- Performance optimization
- Team training

## 📄 License

This project is proprietary and confidential.

## 👥 Team

- **Project Owner**: Manzil Real Estate
- **Development**: Full Stack Team

## 🤝 Contributing

Internal team members only.

---

**Status**: Under Development 🚀  
**Last Updated**: June 2024  
**Version**: 1.0.0-beta
