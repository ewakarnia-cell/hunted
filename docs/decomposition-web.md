# Functional Decomposition - Hunted Web

## 1. Main Page
### 1.1. For Companies
- Display of product info
- Comparison section
- CEO quotes
- Partner logos
- CTA buttons (Sign up, Candidates list)

### 1.2. For Engineers
- Registration form (email + social login)
- Links to Jobs/Web3 companies
- User feedback section (min. 10 entries)
- Mobile app banner (for logged-in users)

## 2. Candidates List
### 2.1. Filters
- **Logged-in users:** Role, Technologies, Salary, English level, Location.
- **Logged-out users:** Hover-triggered sign-in prompt.

### 2.2. Candidate Profile
- Profile details
- Hidden contacts (before chat initiation)
- Experience sorting & "Show experience" expansion
- Opening profile in new tab
- Start chat (for recruiters)
- Candidate card preview (skills/achievements summary)

## 3. Sign Up
- Social login (Google, LinkedIn, GitHub)
- **As a Recruiter:** Multi-field form (Position, Company, Contact info, Role, Tech, Salary, Experience, English, Location) -> Redirect to candidates list.
- **As a Candidate:** Multi-field form (Role, Expectations, Experience, Bio, Contact) -> Profile activation delay (Admin approval 24–48h).

## 4. Sign In
- Login form
- "Sign up" link
- "Forgot password" link

## 5. Chats
- Archive/Favourite chat options
- **As a Recruiter:** Chat initiation, Hidden candidate contacts, Send offer, Reject/Mark as rejected.
- **As a Candidate:** Open/Hide contact details, Recruiter-profile-creation warning.

## 6. Profile
- Dual account roles (Candidate/Recruiter simultaneously)
- Profile creation flow
- **Profile section:** Edit, Switch roles, Connect social accounts, Change password.
- Activation/Deactivation
- Edit profile (Admin access)

## 7. Footer
- TOP 100 Web3 companies (preview 5)
- Vacancies (3 columns)
- Social links (LinkedIn, Twitter, Telegram, Signal, Instagram, Facebook)
- Information links (Docs, Pricing, FAQ, About Us)

## 8. Web3 Companies and Jobs
- Table of 100 companies (groups of 10)
- **Job Posting:** Manual or ATS import (authorized users only)
- **One-click apply:** Authorized users
- **Vacancies Filtering:** Skills filter
- **Unauthorized users:** Limited view + Sign-in prompt on "View more"
- **Subscription form:** Desired roles, Experience, Email
