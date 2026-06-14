# CricketX Pro — Product Overview

## Product Identity
**Name**: CricketX Pro  
**Category**: Mobile App — Sports Scoring & Analytics  
**Platform**: iOS & Android (Flutter)  
**Tagline**: Next-generation cricket scoring — futuristic, precise, premium.  
**Pricing**: Free tier · Premium ₹99/month or ₹499/year · 7-day free trial

---

## Target Users
- **Club organizers & team captains** who need a reliable in-field scorer with stat history
- **Amateur and recreational players** who want beautiful, shareable match records
- **Stats enthusiasts** who track team and player performance across the season

---

## Design Language
Futuristic glassmorphism on a deep-navy base. Electric blue (#00D4FF) and neon purple (#8B5CF6) glowing accents. Smooth animated score updates, holographic-style cards, particle ambient effects, and neon buttons. Mobile-first, every tap target thumb-reachable and legible in sunlight.

**Palette**: Deep Navy `#0A0E27` · Electric Blue `#00D4FF` · Neon Purple `#8B5CF6`  
**Framework**: Flutter · Material 3 Dark Theme

---

## Core Feature Areas

### 1. Match Setup
Configure a match in seconds: Team A & B names, number of overs, toss winner, batting/bowling choice. Fast entry designed for in-field setup before the first ball.

### 2. Live Score Screen
Real-time scoring dashboard displaying: current score (runs/wickets), overs and ball count (e.g. 5.2, 10.4), run rate, second-innings target, required run rate, current batsmen with live stats, current bowler with live figures.

### 3. Ball-by-Ball Controls
One-tap scoring buttons: 0 runs, 1 run, 2 runs, 3 runs, 4 runs, 6 runs, Wicket, Wide, No Ball, Bye, Leg Bye. Plus **Undo Last Ball** action for corrections.

### 4. Over Tracking
Automatic ball counting with over completion detection. Current over displayed in standard format (e.g. "5.2 Overs"). Scrollable over-summary history showing each over's breakdown.

### 5. Team Statistics
Per-innings: total runs, wickets, extras, boundary count (4s + 6s), run rate graph visualised over the innings.

### 6. Player Statistics
**Batting**: runs, balls faced, strike rate, fours, sixes.  
**Bowling**: overs bowled, runs conceded, wickets taken, economy rate.

### 7. Match Summary & Sharing
Result screen: winning team, margin of victory, full scorecard, Man of the Match selector, and share-scorecard-as-image export.

---

## Authentication & User Accounts

### Login Methods
Email & Password · Google Sign-In · Phone Number (OTP) · Guest mode (no account required)

### Registration
Name, email, password, optional profile picture.

### User Profile
Username, profile photo, matches played, matches won, premium status badge, edit profile.

### Security
Firebase Authentication · password reset via email · secure sessions · logout.

### Cloud Sync
Match data saved to Firebase Firestore. Automatic sync across all signed-in devices. Scorecard backup runs automatically.

---

## Monetization

### Free Tier
- Basic ball-by-ball score tracking
- Team management
- Match summary
- Last 5 matches of history

### Premium (₹99/month · ₹499/year · 7-day free trial)
- Unlimited match history
- Advanced player statistics
- AI-powered match insights
- Custom team logos
- Premium futuristic themes
- Cloud backup & sync (Firestore)
- Ad-free experience
- Export scorecards as PDF and images
- Live score sharing via shareable link
- Gold/Neon premium badge
- Animated premium card UI

### Purchase Infrastructure
- RevenueCat for cross-platform subscription management
- Google Play Billing Library (Android)
- Apple StoreKit (iOS)
- Subscription management screen with restore purchases option
- Feature comparison table
- Locked premium features display upgrade prompts to free users
- Secure backend validation via RevenueCat webhooks

---

## Technology Stack

| Layer | Choice |
|---|---|
| App Framework | Flutter |
| Backend & Database | Firebase Firestore |
| Authentication | Firebase Authentication |
| Design System | Material 3 Dark |
| Subscription Management | RevenueCat |
| Android Billing | Google Play Billing Library |
| iOS Billing | Apple StoreKit |
| Auth Providers | Firebase Auth · Google Sign-In SDK · OTP |

---

## Strategic Principles
1. **In-field first** — every control is one tap, every label readable in sunlight.
2. **Stats delight** — beautiful, shareable scorecards are the primary viral loop.
3. **Freemium monetization** — generous free tier builds trust; premium converts on history depth and export.
4. **Cross-device continuity** — Firebase sync means score on one phone, review on any device.
5. **Platform-native billing** — RevenueCat abstracts Play + StoreKit for a single subscription codebase.
