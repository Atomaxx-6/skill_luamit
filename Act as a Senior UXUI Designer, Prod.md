# Beauty & Cosmetics POS System
Version: 1.0

---

# PROJECT OVERVIEW

Act as a Senior UX/UI Designer, Product Designer, Solution Architect, Business Analyst, Database Architect, and Senior Full Stack Developer with 15+ years of experience.

Design and generate a production-ready enterprise-grade Beauty & Cosmetics POS System suitable for real-world commercial deployment.

The system must follow modern software engineering standards and should look, feel, and function like a product built by Microsoft, Stripe, Shopify, Square, or Notion.

---

# BUSINESS OVERVIEW

Create a complete Point of Sale (POS) and Retail Management System for cosmetics and skincare businesses.

Business Types:

- Single Store
- Multi Branch Retail
- Franchise Chain
- Beauty Clinic Retail
- Cosmetics Distributor

Target Businesses:

- Cosmetics Store
- Beauty Retail Shop
- Skincare Store
- Perfume Store
- Beauty Clinic
- Health & Beauty Retail

---

# PROJECT GOALS

Primary Goals:

- Fast Checkout Experience
- Accurate Inventory Management
- Customer Loyalty Management
- Promotion Automation
- Business Analytics
- Multi-Branch Management
- Real-Time Reporting

Secondary Goals:

- Scalability
- Security
- Ease of Use
- Maintainability
- Mobile Accessibility

---

# USER ROLES

## Cashier

Responsibilities:

- Process Sales
- Search Products
- Process Returns
- Manage Customer Records
- Apply Promotions
- Accept Payments

Permissions:

- Create Transactions
- View Products
- View Customers

---

## Store Manager

Responsibilities:

- Inventory Monitoring
- Employee Performance
- Sales Monitoring
- Promotion Management

Permissions:

- Inventory Adjustment
- Reporting
- Employee Monitoring

---

## Admin

Responsibilities:

- User Management
- Role Management
- System Configuration

Permissions:

- Full System Access

---

## Business Owner

Responsibilities:

- Financial Monitoring
- KPI Monitoring
- Strategic Decisions

Permissions:

- View All Reports
- Multi-Branch Visibility

---

# CORE MODULES

## Dashboard

Features:

- Today's Sales
- Monthly Revenue
- Gross Profit
- Net Profit
- Transaction Count
- Average Order Value
- Best Selling Products
- Top Customers
- Low Stock Alert
- Expiring Product Alert
- Branch Comparison
- Growth Trends

---

## Point Of Sale

Features:

- Barcode Scanning
- Product Search
- SKU Search
- Quick Checkout
- Shopping Cart
- Discount Application
- Coupon Usage
- Loyalty Point Redemption
- Returns And Refunds
- Receipt Printing
- Receipt Reprint

Payment Methods:

- Cash
- Credit Card
- Debit Card
- QR Payment
- Bank Transfer
- E-Wallet

---

## Inventory Management

Features:

- Product Management
- Brand Management
- Category Management
- Supplier Management
- SKU Management
- Batch Tracking
- Lot Tracking
- Expiry Tracking
- Stock Transfer
- Stock Adjustment
- Inventory Count
- Stock Valuation

---

## Customer Relationship Management

Features:

- Customer Profile
- Membership Registration
- Loyalty Program
- Reward Points
- Purchase History
- Birthday Rewards
- Customer Segmentation
- Customer Notes

Membership Tiers:

- Bronze
- Silver
- Gold
- Platinum

---

## Promotion Engine

Features:

- Discount Coupons
- Buy X Get Y
- Bundle Promotions
- Category Promotions
- Brand Promotions
- Seasonal Campaigns
- Member Discounts
- Birthday Discounts

---

## Reports & Analytics

Features:

- Sales Reports
- Profit Reports
- Inventory Reports
- Customer Reports
- Product Performance Reports
- Branch Performance Reports
- Employee Performance Reports
- Promotion Effectiveness Reports

Export Formats:

- Excel
- PDF
- CSV

---

# WORKFLOWS

## Product Receiving

Supplier
↓
Receive Products
↓
Quality Check
↓
Inventory Update
↓
Available For Sale

---

## Sales Workflow

Customer
↓
Product Selection
↓
Apply Promotion
↓
Payment
↓
Receipt Generation
↓
Customer History Update
↓
Reporting Update

---

## Return Workflow

Customer Request
↓
Receipt Verification
↓
Approval
↓
Inventory Update
↓
Refund

---

# NAVIGATION STRUCTURE

Dashboard

Sales
├── POS
├── Transactions
├── Returns
└── Daily Summary

Products
├── Products
├── Categories
├── Brands
└── Suppliers

Inventory
├── Stock Overview
├── Stock Movement
├── Stock Adjustment
├── Transfers
└── Stock Count

CRM
├── Customers
├── Memberships
├── Loyalty Points
└── Customer Segments

Promotions
├── Coupons
├── Campaigns
├── Discounts
└── Bundles

Reports
├── Sales Reports
├── Profit Reports
├── Inventory Reports
├── Customer Reports
└── Analytics Dashboard

Security
├── Users
├── Roles
└── Audit Logs

Settings

---

# UI DESIGN REQUIREMENTS

Looks Like:

- Microsoft 365 Admin Center
- Azure Portal
- Stripe Dashboard
- Shopify Admin
- Square POS
- Notion
- Linear
- Vercel Dashboard

---

# DESIGN PRINCIPLES

- Enterprise Grade
- Premium Beauty Brand
- Professional Retail Software
- Data Dense Design
- Accessibility Compliant
- Mobile Friendly
- Touch Friendly
- Fast Workflow Focused
- Clean Interface
- Minimal Visual Noise

---

# DESIGN SYSTEM

## Typography

Primary Font:

- Inter

Secondary Font:

- Segoe UI

Font Weights:

- 400 Regular
- 500 Medium
- 600 SemiBold
- 700 Bold

---

## Grid System

- 8px Spacing System

Spacing:

- 4px
- 8px
- 12px
- 16px
- 24px
- 32px
- 48px
- 64px

---

## Border Radius

Small:
8px

Medium:
12px

Large:
16px

---

# COLOR SYSTEM

## Primary

Purple 700

HEX:

#6D28D9

---

## Secondary

Pink 600

HEX:

#DB2777

---

## Success

HEX:

#16A34A

---

## Warning

HEX:

#D97706

---

## Danger

HEX:

#DC2626

---

## Info

HEX:

#2563EB

---

## Neutral Gray Scale

50 : #F9FAFB

100 : #F3F4F6

200 : #E5E7EB

300 : #D1D5DB

400 : #9CA3AF

500 : #6B7280

600 : #4B5563

700 : #374151

800 : #1F2937

900 : #111827

---

# VISUAL CHARACTERISTICS

- Consistent Design System
- Fluent Design Principles
- High Information Density
- Data First Layout
- Professional SaaS Design
- Soft Shadows
- Subtle Glass Effects
- Fast Navigation
- Clear Visual Hierarchy

---

# DARK MODE

Must Support:

- Light Theme
- Dark Theme

Theme Switching:

- Automatic
- Manual

---

# RESPONSIVE REQUIREMENTS

Desktop First

Breakpoints:

Mobile:
320px+

Tablet:
768px+

Laptop:
1024px+

Desktop:
1440px+

Wide Screen:
1920px+

---

# ACCESSIBILITY REQUIREMENTS

Must Follow:

- WCAG 2.1 AA
- Keyboard Navigation
- Screen Reader Compatibility
- Color Contrast Compliance
- Accessible Forms

---

# DATABASE DESIGN

Core Tables:

Users

Roles

Permissions

Customers

Memberships

Products

ProductImages

Brands

Categories

Suppliers

InventoryBalances

InventoryTransactions

Sales

SaleItems

Payments

Returns

Promotions

Coupons

Branches

AuditLogs

Notifications

Settings

---

# API DESIGN

Authentication

POST /api/auth/login

POST /api/auth/logout

POST /api/auth/refresh

POST /api/auth/register

---

Products

GET /api/products

GET /api/products/{id}

POST /api/products

PUT /api/products/{id}

DELETE /api/products/{id}

---

Customers

GET /api/customers

POST /api/customers

PUT /api/customers/{id}

---

Sales

GET /api/sales

GET /api/sales/{id}

POST /api/sales

POST /api/sales/refund

---

Inventory

GET /api/inventory

POST /api/inventory/adjustment

POST /api/inventory/transfer

---

# ARCHITECTURE

Frontend

Next.js
React
TypeScript
Tailwind CSS
shadcn/ui

↓

Supabase

↓

Application Layer

↓

Domain Layer

↓

Infrastructure Layer

↓

PostgreSQL

---

# SECURITY REQUIREMENTS

Authentication:

- JWT
- Refresh Token

Authorization:

- RBAC

Security Features:

- Audit Trail
- Login History
- Password Policy
- Session Management
- Rate Limiting

---

# NON FUNCTIONAL REQUIREMENTS

Performance:

- Dashboard < 2 seconds
- POS Checkout < 1 second

Availability:

- 99.9%

Scalability:

- Support 100+ Stores
- Support 500+ Concurrent Users

---

# TECH STACK

Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- shadcn/ui

Backend

- Supabase

Database

- PostgreSQL

Patterns

- Clean Architecture
- CQRS
- Repository Pattern
- Unit Of Work
- MediatR

---

# AVOID

Do Not Generate:

- Generic AI Design
- Bootstrap Appearance
- Admin Template Style
- Large Empty Spaces
- Excessive Gradients
- Oversized Cards
- Marketing Site Layout
- Generic Dashboard Concepts
- Fake Charts
- Unrealistic Statistics

---

# OUTPUT REQUIREMENTS

Generate All Of The Following:

1. Complete Sitemap

2. User Flows

3. Wireframes

4. UI Mockups

5. Design System

6. Component Library

7. Database Schema

8. ER Diagram

9. API Specification

10. Folder Structure

11. Frontend Architecture

12. Backend Architecture

13. Security Architecture

14. Deployment Architecture

15. Production Ready Source Code

16. Test Cases

17. User Acceptance Criteria

18. Documentation

---

# FINAL INSTRUCTION

Think Like:

- Senior Product Manager
- Senior Business Analyst
- Senior UX Researcher
- Senior UX/UI Designer
- Solution Architect
- Database Architect
- Lead Frontend Engineer
- Lead Backend Engineer

Challenge assumptions.

Design for real operational use.

Prioritize:

- Usability
- Maintainability
- Scalability
- Security
- Profitability

Do not generate generic AI style layouts.

Generate a system that could realistically be shipped by Microsoft, Stripe, Shopify, Square, or a modern SaaS company.