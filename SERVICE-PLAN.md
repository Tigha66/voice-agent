# ClawdVoice - AI Voice Agent Service

## Service Overview

**ClawdVoice** — AI voice agents powered by OpenClaw + ClawdTalk + Telnyx

---

## What You Get

### Features
- 📞 **Inbound Calls** — AI answers calls, handles FAQs, creates tickets
- 📞 **Outbound Calls** — AI calls leads, qualifies, schedules
- 💬 **SMS Automation** — Text follow-ups, reminders, confirmations
- 📅 **Calendar Integration** — Schedule appointments automatically
- 🎫 **Ticket Creation** — Zendesk, Jira, HubSpot integration
- 🌐 **Web Search** — Real-time info during calls

---

## Service Tiers

| Feature | Basic | Pro | Enterprise |
|---------|-------|-----|------------|
| **Price** | $99/mo | $299/mo | $999/mo |
| **SMS Only** | ✅ | ✅ | ✅ |
| **Voice Calls** | — | ✅ | ✅ |
| **Minutes/month** | Unlimited | 500 | Unlimited |
| **Inbound Lines** | 1 | 3 | 10 |
| **Languages** | 1 | 3 | Unlimited |
| **Custom Voice** | — | ✅ | ✅ |
| **Integrations** | Basic | Advanced | Custom |
| **Setup** | $199 | $499 | $1,999 |

---

## Use Cases

### 1. Appointment Reminder Calls
- Automated reminder calls 24h before appointments
- Confirmation → reschedule → cancel flow
- Integration with Calendly, Google Calendar
- **Perfect for:** Medical, dental, salon, consulting

### 2. Inbound Support Line
- 24/7 AI answers common questions
- FAQ handling → ticket creation → escalation
- **Perfect for:** IT support, logistics, e-commerce

### 3. Outbound Lead Qualification
- AI calls leads automatically
- Qualify → schedule demo → notify sales
- **Perfect for:** Real estate, insurance, SaaS

### 4. SMS Follow-Up Sequences
- Automated text follow-ups
- Appointment confirmations
- Payment reminders
- **Perfect for:** All businesses

---

## Setup Process

### Step 1: Telnyx Account
1. Go to [telnyx.com](https://telnyx.com)
2. Sign up → Add payment
3. Buy phone number: ~$1-5/month
4. Enable Voice API

**Cost:** $1-5/month for phone number + $0.01-0.05/min for calls

### Step 2: Install ClawdTalk
```bash
npx clawhub install clawdtalk
```

### Step 3: Configure Skills
```bash
# Calendar integration
npx clawhub install gog

# Web search
npx clawhub install brave-search
```

### Step 4: Connect to OpenClaw
```bash
# Set environment variables
export TELNYX_API_KEY=your_key
export TELNYX_PHONE_NUMBER=+1234567890

# Start ClawdTalk
./scripts/connect.sh start
```

---

## Cost Structure

### Your Costs (Monthly)

| Item | Cost |
|------|------|
| Telnyx Phone Number | $2-5/month |
| Voice Minutes (500 min) | $10-25/month |
| SMS (1000) | $5-10/month |
| OpenClaw Hosting | $0-20/month |
| **Total Cost** | **$17-60/month** |

### Your Profit

| Tier | Price | Your Cost | Profit |
|------|-------|-----------|--------|
| Basic | $99 | $20 | $79/mo |
| Pro | $299 | $40 | $259/mo |
| Enterprise | $999 | $60 | $939/mo |

---

## Quick Start Guide

### 1. Get Telnyx Account
1. Register at telnyx.com
2. Add $50 credit
3. Buy phone number

### 2. Set Up ClawdTalk
```bash
# Install
npx clawhub install clawdtalk

# Configure
export TELNYX_API_KEY=your_api_key
export TELNYX_PUBLIC_KEY=your_public_key
```

### 3. Test Setup
```bash
# Make test call
telnyx call out +1234567890
```

---

## Example Scripts

### Appointment Reminder
```
"Hello, this is a reminder from [Company]. You have an appointment tomorrow at [TIME]. 
Press 1 to confirm, 2 to reschedule, 3 to cancel."
```

### Lead Qualification
```
"Hi, I'm calling from [Company]. Do you have 2 minutes? 
I'm reaching out because we help businesses like yours [benefit]. 
Are you currently looking for a solution?"
```

### FAQ Response
```
Customer: "What are your hours?"
AI: "We're open Monday to Friday, 9am to 6pm. Is there anything else I can help you with?"
```

---

## Target Markets

| Market | Pain Point | Solution |
|--------|-----------|----------|
| Dental/Medical | Missed appointments | Auto-reminders |
| Real Estate | Missed leads | 24/7 answering |
| IT Support | After-hours calls | AI triage |
| E-commerce | Customer questions | FAQ bot |
| Logistics | Driver coordination | SMS updates |

---

## Next Steps

1. ✅ Create Telnyx account
2. ⬜ Buy phone number
3. ⬜ Install ClawdTalk skill
4. ⬜ Test with sample calls
5. ⬜ Create landing page
6. ⬜ Get first customer

---

*Plan created: 2026-03-01*
