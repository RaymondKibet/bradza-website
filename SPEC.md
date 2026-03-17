# BRADZA Co Ltd Website Specification

## 1. Project Overview

**Project Name:** BRADZA Co Ltd - Member Portal & Information Hub  
**Project Type:** Single-page web application  
**Core Functionality:** A website that showcases BRADZA Co Ltd, enables borrowers to learn about the company, tracks group finances, meetings, welfare, and investments.  
**Target Users:** Members/borrowers of BRADZA Co Ltd, potential members, and community visitors.

---

## 2. UI/UX Specification

### Layout Structure

**Navigation Bar (Fixed)**
- Logo: BRADZA with green/yellow accent
- Navigation links: Home, About, Dashboard, Services, Contact
- Mobile: Hamburger menu

**Sections:**
1. Hero Section - Brand intro with animated elements
2. About Section - Company story and mission
3. Directors Section - Team profiles with photos
4. Services Section - What they offer (loans, savings)
5. Dashboard Section - Financial tracking interface
6. Growth Ideas Section - Creative features for expansion
7. Social Media Section - IB&B platform links
8. Contact Section - Form and info

### Visual Design

**Color Palette:**
- Primary Green: `#006B3F` (Kenyan flag red)
- Primary Yellow: `#FFD900` (Australian flag yellow)
- Australian Green: `#00A651`
- Accent Gold: `#F4D03F`
- Dark Background: `#1A1A2E`
- Card Background: `#16213E`
- Text Light: `#EAEAEA`
- Text Muted: `#A0A0A0`
- Success: `#2ECC71`
- Warning: `#F39C12`
- Danger: `#E74C3C`

**Typography:**
- Headings: 'Playfair Display', serif (bold, dramatic)
- Body: 'Poppins', sans-serif (modern, clean)
- Accent: 'Orbitron', sans-serif (futuristic numbers/stats)

**Spacing:**
- Section padding: 80px vertical
- Card padding: 24px
- Element gaps: 16px/24px

**Visual Effects:**
- Glassmorphism cards with backdrop blur
- Gradient overlays using green/yellow
- Subtle floating animations
- Hover lift effects on cards
- Progress bars with animated fills
- Particle/geometric background patterns

### Components

**Director Cards:**
- Circular avatar placeholder with initials
- Name, title, brief bio
- Social links
- Hover: scale + glow effect

**Dashboard Widgets:**
- Total Savings display (animated counter)
- Active Loans tracker
- Expenses summary
- Meeting calendar
- Welfare fund status
- Investment portfolio breakdown
- Recent transactions list

**Service Cards:**
- Icon representation
- Title and description
- CTA button

**Transaction List:**
- Date, description, amount, type
- Color-coded by category
- Filter tabs

**Loan Calculator Widget:**
- Input: amount, interest rate, term
- Output: monthly payment, total interest

---

## 3. Functionality Specification

### Core Features

**1. About Us Page**
- Company history and mission
- Origin story (Kenyan-Australian connection)
- Values and vision

**2. Director Profiles**
- ZANDE AYUB - Chairman
- DANIEL KIPRONO - Secretary
- BARNABAS KENEI - Treasurer
- RAYMOND KIBET - General Organising Secretary & Welfare

**3. Financial Dashboard (Interactive)**
- Savings tracker with weekly contribution display
- Loan portfolio with borrower names and amounts
- Expense categories with pie chart
- Welfare fund allocation
- Investment returns tracker

**4. Meeting Tracker**
- Upcoming meetings calendar view
- Past meeting minutes summary
- Action items tracker

**5. Services Display**
- Member loans information
- Interest rates
- Application process
- Savings products

**6. Contact Form**
- Name, email, message fields
- Form validation
- Success feedback

### Creative Growth Ideas (Added)

**1. Milestone Tracker**
- Visual progress toward group goals
- Target amount thermometer
- Monthly achievement badges

**2. Investment Opportunities Board**
- List of potential investments
- ROI projections
- Voting system for members

**3. Educational Hub**
- Financial literacy resources
- Investment tips
- Success stories

**4. Member Spotlight**
- Featured member achievements
- Testimonials

**5. Newsletter Signup**
- Email subscription for updates

**6. Loan Calculator**
- Interactive repayment calculator

**7. Goal Tracker**
- Multiple savings goals
- Progress visualization

**8. Dark/Light Theme Toggle**
- User preference persistence

### User Interactions

- Smooth scroll navigation
- Animated number counters on scroll
- Tab switching for dashboard sections
- Modal for detailed transaction view
- Form validation with inline errors
- Toast notifications for actions

### Data Handling

- LocalStorage for demo data persistence
- Sample data pre-populated
- Export functionality for reports (CSV format)

---

## 4. Acceptance Criteria

1. ✓ Website loads without errors
2. ✓ All 4 directors displayed with correct titles
3. ✓ Dashboard shows all financial widgets
4. ✓ Meeting tracker displays calendar
5. ✓ Social media links work (placeholder URLs)
6. ✓ Color scheme matches green/yellow theme
7. ✓ Responsive on mobile, tablet, desktop
8. ✓ Animations smooth and performant
9. ✓ Contact form validates and shows feedback
10. ✓ All growth ideas sections visible
11. ✓ Loan calculator functions correctly
12. ✓ Dark theme toggle works
