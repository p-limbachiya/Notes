# KRUX Finance - Tech Intern Assessment

## 📋 Overview
Build a customer support system that demonstrates your ability to work with the same
technologies we use in our production application.

## 🎯 Take-Home Assignment: Dual Chatbot System

### Project Requirements
Build a comprehensive customer support system with **two distinct interfaces**:
1. **Customer Chatbot** - For end users seeking help with loans  
2. **Support Executive Dashboard** - For customer support agents to manage conversations

### Technical Stack Requirements
Use the **same technologies as KRUX Finance v2**:
- **Next.js 14+** with **TypeScript** (App Router)
- **Tailwind CSS** for styling
- **React Hook Form** with **Zod** validation
- **Lucide React** icons
- **Context API** for state management
- Any **component library** of your choice
- **Local storage** for data persistence (no backend required)
- **Mock authentication** (sample users)

---

## Core Features Overview

### Page 1: Customer Chatbot Interface

#### Customer Chat Experience
**What customers should be able to do:**
- Start a conversation about loan applications
- Ask questions about document requirements
- Check their application status
- Request to speak with a human agent
- Get helpful responses from an automated bot

**UI/UX Requirements:**
- Mobile-first design (like WhatsApp/Telegram)
- Clean, professional interface matching KRUX Finance branding
- Typing indicators and message timestamps
- Smooth scrolling and responsive design

---

#### Bot Conversation Flows
**The bot should handle these scenarios:**

**Loan Application Help:**
- Guide users through loan application process
- Explain different loan types (Business, Personal, MSME)
- Provide application requirements and next steps

**Document Requirements:**
- List required documents for different loan types
- Explain document formats and specifications
- Help with document-related queries

**Application Status:**
- Allow users to check their application status
- Provide realistic status updates and timelines
- Handle cases where application ID is not found

**Escalation to Human Agent:**
- Seamlessly transfer users to human support
- Create support tickets for agent follow-up
- Maintain conversation context during transfer

---

### Page 2: Support Executive Dashboard

#### Support Agent Experience
**What support agents should be able to do:**
- View all customer support tickets in a queue
- See ticket priorities and categories
- Chat with customers in real-time
- Access customer information and loan history
- Use quick reply templates
- Resolve, escalate, or transfer tickets
- Track response times and performance

#### Dashboard Layout
**Suggested interface structure:**
- **Left Panel**: Ticket queue with priority indicators
- **Right Panel**: Active conversation with customer
- **Top Bar**: Agent status, notifications, search
- **Bottom**: Message input with agent tools

---

#### Agent Tools & Features
**Essential agent functionality:**
- **Quick Reply Templates**: Pre-written responses for common queries
- **Customer Information Panel**: Display customer's loan applications and status
- **Ticket Management**: Ability to resolve, escalate, or transfer conversations
- **Internal Notes**: Private notes not visible to customers
- **Response Time Tracking**: Monitor how long customers wait for responses
- **Real-time Synchronization**: Updates between customer chat and agent dashboard

---

### Application Structure
**Create a Next.js application with these pages:**
- **Landing Page**: Navigation between customer chat and support dashboard
- **Customer Chat Page**: `/customer-chat` - Public access for customers
- **Support Dashboard**: `/support-dashboard` - Protected access for agents

---

### Authentication System
**Implement simple mock authentication:**

---

### Data Management
**Use localStorage to store:**
- Chat conversations and message history
- Support tickets and their status
- User sessions and authentication state
- Agent notes and customer information

---

### State Management
**Use React Context API and useReducer for:**
- Managing chat messages and conversation state
- Handling support ticket queue and updates
- Synchronizing data between customer and agent interfaces
- Managing authentication and user sessions

---

## Bonus Features (Extra Credit)
**Implement any of these for additional points:**
1. **Quick Reply Templates** - Pre-defined responses for agents  
2. **File Upload Simulation** - Mock document upload functionality  
3. **Chat History Persistence** - Save and restore conversation history  
4. **Real-time Simulation** - Use polling or intervals for live updates  
5. **Dark/Light Mode** - Theme switching for both interfaces  
6. **Voice Input** - Speech-to-text using browser APIs  
7. **Performance Metrics** - Track agent response times  
8. **Customer Satisfaction** - Post-chat rating system  
9. **Search Functionality** - Search through tickets and conversations  
10. **Notification System** - Visual/audio alerts for new messages  

---

## Sample Login Credentials

**Customer:**
- Phone: +919876543210 (Rahul Sharma)  
- Phone: +919876543211 (Priya Patel)

**Agent:**
- Username: amit.kumar (Support Agent)  
- Username: sneha.singh (Senior Agent)

---

## Features Implemented
- [x] Customer chat interface  
- [x] Support dashboard interface  
- [x] Bot conversation flows  
- [x] Mock authentication  
- [x] Local storage data persistence  
- [ ] Voice input (bonus)

---

#### 3. Live Demo
- Deploy to **any hosting platform** (Vercel, Netlify, GitHub Pages, etc.)
- Provide live demo URL
- Include demo credentials in your README
- Ensure both customer and agent interfaces work in production

---

### Time Limit
**1-2 days** from assignment delivery
