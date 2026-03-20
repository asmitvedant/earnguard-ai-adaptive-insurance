Here's your final README with the "Judges' Takeaway" quote removed and no other extraneous content. It's ready for submission.

---

# EarnGuard AI – Adaptive Hyperlocal Prophet
### Next-Gen Parametric Income Protection for India's Food Delivery Heroes
#### Guidewire DEVTrails 2026 – Phase 1 Submission

<p align="center">
  <img src="https://img.shields.io/badge/status-🚀%20INSANE-brightgreen" />
  <img src="https://img.shields.io/badge/pricing-💰%20Weekly%20Compliant-blue" />
  <img src="https://img.shields.io/badge/fraud%20detection-🛡️%205--Layer%20AI%20Fortress-red" />
  <img src="https://img.shields.io/badge/grid-🗺️%20Adaptive%20(100m--1km)-orange" />
  <img src="https://img.shields.io/badge/anti--spoofing-🔒%20Multi--Modal%20Fusion-purple" />
  <img src="https://img.shields.io/badge/AI-4%20Models%20%7C%20XGBoost%20%7C%20GNN-blue" />
  <img src="https://img.shields.io/badge/license-MIT-yellow" />
  <img src="https://img.shields.io/badge/ATS%20Ready-✅%20Optimized-brightgreen" />
</p>

---

## Table of Contents
- [The Human Crisis](#the-human-crisis)
- [The Gig Economy Emergency](#the-gig-economy-emergency)
- [Our Persona: Food Delivery Partners](#our-persona-food-delivery-partners)
- [Our INSANE Solution: Adaptive Hyperlocal Prophet](#our-insane-solution-adaptive-hyperlocal-prophet)
 - [System Architecture – EarnGuard AI](#system-architecture--earnguard-ai)
- [Hyperlocal Risk Scoring (5‑Source Fusion)](#hyperlocal-risk-scoring-5source-fusion)
- [Weekly Premium Model – Personalized & Fair](#weekly-premium-model--personalized--fair)
- [Parametric Triggers – 5+ Automated Events](#parametric-triggers--5-automated-events)
- [Platform Choice: Mobile‑First Experience](#platform-choice-mobilefirst-experience)
- [AI/ML Integration – 4 Core Models](#aiml-integration--4-core-models)
- [Fraud Detection – 5‑Layer AI Fortress](#fraud-detection--5layer-ai-fortress)
- [Adversarial Defense & Anti-Spoofing Strategy](#adversarial-defense--anti-spoofing-strategy)
- [Tech Stack & Architecture](#tech-stack--architecture)
- [6‑Week Development Roadmap](#6week-development-roadmap)
- [Team](#team)
- [Links & Resources](#links--resources)
- [Compliance Matrix](#compliance-matrix)


---

## The Human Crisis

**Meet Arjun.** 22 years old. He weaves through Mumbai's chaotic traffic 12 hours a day, delivering hot meals for Zomato. He dreams of saving enough to send his younger sister to college. But when the monsoon hits, his earnings vanish like water on hot asphalt. Last August, relentless rains stole ₹5,200 from his pocket – money meant for her fees. He borrowed from a local moneylender at 5% daily interest. The debt spiral tightened.

**Meet Sunita.** 28, single mother in Bangalore. She delivers Swiggy orders from dawn until midnight. When a sudden curfew locked down her area, she lost ₹800 in cancelled orders – her daughter's monthly asthma medicine money. No insurance helped. No safety net.

**Meet Ramesh.** 35, Delhi. Family of five depends on his Zomato earnings. When pollution (AQI >400) forced him indoors for 10 days last winter, he lost ₹6,200. *"Hum zinda hai, par kamai mari hui hai."* (We are alive, but our earnings are dead.)

They are not alone. **15 million Indian gig workers** face this daily. They are the backbone of our digital economy, yet they have zero protection against the whims of weather, pollution, or politics.

---

## The Gig Economy Emergency

- **20–30% monthly income loss** due to external disruptions (rain, heat, pollution, curfews, strikes).
- **No insurance covers income loss** – only health, accidents, vehicles.
- Workers fall into **debt traps**, mental stress, and often quit the platform.
- **Current insurance?** Useless for income loss. The market is broken.

---

## Our Persona: Food Delivery Partners (Zomato/Swiggy)

| Why Food Delivery? | Key Characteristics |
|--------------------|---------------------|
| Largest gig segment – maximum impact | Daily earnings: ₹600–1,200 |
| Highly vulnerable to weather & curfews | Work 6–7 days/week, 10–14 hours/day |
| Emotional connection – every Indian uses these apps | Often migrant workers, family breadwinners |
| Untapped by parametric insurance | High frequency of disruptions |

---

## Our INSANE Solution: Adaptive Hyperlocal Prophet

Instead of boring fixed grids, we built an **adaptive grid system** (quadtree) that **changes resolution based on risk density**. This is a **paradigm shift** in hyperlocal risk modeling.

### How It Works
- **Low‑risk areas** (e.g., T Nagar in Chennai) → **1km × 1km grids** – efficient, no wasted compute.
- **High‑risk areas** (e.g., Velachery flood zone in Chennai, Andheri traffic hotspots) → **100m × 100m micro‑grids** – 25× more precision where it matters.
  
![Adaptive Grid](adaptive%20grid.png)

**Why this is INSANE:**
- **Computationally efficient** – focuses power where risk is real.
- **Pinpoint accuracy** – can detect flooding on a specific street corner.
- **Scalable** – covers entire cities without explosion of cells.
- **No other team will think of this** – guaranteed differentiation.


---
## System Architecture – EarnGuard AI

<p align="center">
  <img src="./System Architecture.png" alt="EarnGuard AI Architecture Diagram" width="1000"/>
</p>

<p align="center">
  Real-time AI-powered risk prediction • Parametric automation • Fraud-proof trust engine
</p>

---

## Hyperlocal Risk Scoring (5‑Source Fusion)

Every **15 minutes**, each cell’s risk is updated using a synergistic fusion of 5 data sources:

| Source | Weight | API / Method | Description |
|--------|--------|--------------|-------------|
| **Base Risk** (historical) | 30% | Govt flood maps, pollution history, traffic patterns | Derived from past claims, flood zone data, and traffic density. |
| **Weather** (real‑time) | 30% | OpenWeatherMap (rain intensity, temperature) | Rainfall (mm/hr), temperature (°C). |
| **Pollution** (real‑time) | 20% | WAQI (AQI) | Air Quality Index (0–500). |
| **Traffic** (real‑time) | 10% | Google Maps mock (congestion level) | Congestion score (0–1). |
| **Crowdsourced Reports** | 10% | Worker‑submitted, verified by consensus (≥3 reports) | Reports of waterlogging, strikes, etc. |

**Risk Formula:**
```
Cell Risk = (Base × 0.3) + (Weather × 0.3) + (Pollution × 0.2) + (Traffic × 0.1) + (Crowd × 0.1)
```
All values normalized to 0–1.

**Example – Andheri Grid at 3pm:**
- Base: 0.6 (flood‑prone) ×0.3 = 0.18
- Weather: Heavy rain (0.9) ×0.3 = 0.27
- AQI: 150 → 0.3 ×0.2 = 0.06
- Traffic: 0.8 ×0.2 = 0.16
- Crowd: 2 flood reports → 0.2 ×0.1 = 0.02
- **Total = 0.69 → ORANGE ALERT (Medium-High Risk)**

---

## Weekly Premium Model – Personalized & Fair

We strictly follow the **weekly pricing rule** – premium calculated **once every Monday**, zero per‑trip charges. This is a **game-changer** for gig worker affordability.

### Personalized Premium Formula
```python
premium = base_price × (0.7 + 0.6 × worker_avg_risk)
```
- **base_price**: ₹20 (Basic), ₹35 (Pro), ₹50 (Elite)
- **worker_avg_risk**: Weighted average risk of all adaptive‑grid cells the worker visited in the last 4 weeks, using **next week’s forecast** for those cells (from our ML model).

### Coverage Tiers
| Plan | Weekly Premium Range | Daily Coverage | Payout % |
|------|----------------------|----------------|----------|
| Basic | ₹14 – ₹26 | Up to ₹200 loss | 70% |
| Pro   | ₹25 – ₹46 | Up to ₹400 loss | 80% |
| Elite | ₹35 – ₹65 | Up to ₹700 loss | 90% |

### Real Examples
| Worker | Avg Risk | Plan | Premium |
|--------|----------|------|---------|
| Arjun (mixed) | 0.57 | Pro | ₹36 |
| Ramesh (high‑risk) | 0.85 | Pro | ₹42 |
| Sunita (safe) | 0.25 | Pro | ₹30 |

**Why this works:** Fairness, transparency, and full compliance. Workers pay only for their actual risk exposure.

---

## Parametric Triggers – 5+ Automated Events

We monitor these in real time and auto‑trigger claims when thresholds are crossed – **zero human intervention**.

| Trigger | Threshold | Data Source | Action |
|---------|-----------|-------------|--------|
| Heavy Rain | >50mm in 6h | OpenWeatherMap | Auto-claim for workers in affected grids |
| High Pollution | AQI >350 | WAQI | Auto-claim for workers in those grids |
| Extreme Heat | >42°C | OpenWeatherMap | Auto-claim (critical for delivery safety) |
| Curfew | Govt announcement | NewsAPI + crowdsourced | Auto-claim for workers in zone |
| Strike | Verified reports | NewsAPI + crowdsourced | Auto-claim for workers in zone |
| App Outage | Downtime >30min | Mock platform API | Auto-claim for all active workers |

**Auto‑claim condition:**  
`disruption_score > 0.6 AND predicted_loss > ₹200`

### Claim Calculation
```
Expected Earnings = Worker's avg for that day/time (last 4 weeks)
Loss = Expected Earnings × (Cell Risk × Affected Hours / Daily Hours)
Payout = min(Loss × Coverage %, Policy Cap)
```
*Example: Arjun expected ₹600 for 4h, cell risk 0.9, 3h affected → Loss = ₹405 → Pro pays ₹324 instantly.*

---

## Platform Choice: Mobile‑First Experience

**Why Mobile?**  
- Delivery partners are **always on the move** – they need instant alerts, GPS tracking, and one‑tap reporting.  
- Mobile enables **real‑time risk updates** and **push notifications** for proactive safety.  
- Adoption is higher – no need to boot a laptop after a long shift.

**Tech:** React Native (cross‑platform iOS/Android) with Mapbox GL for adaptive grid visualization.

### Worker App Features
- **Adaptive Grid Map** – color‑coded risk overlay (red/orange/green).
- **Weekly Premium Display** – personalized amount with breakdown.
- **Real‑time Alerts** – “High risk in Andheri – coverage boosted.”
- **One‑Tap Reporting** – report floods/strikes instantly.
- **Auto‑Claim Status** – see payouts in real time.

### Admin Dashboard (Web)
- Live grid heatmap with drill‑down to 100m cells.
- Fraud alerts console with trust scores.
- Predictive analytics: next week’s hotspots.
- Business metrics: loss ratios, active policies, total payouts.

---

## AI/ML Integration – 4 Core Models

We deploy **4 specialized ML models** to power the platform – an **ensemble learning ecosystem**:

| Model | Purpose | Algorithm | Input Features | Output |
|-------|---------|-----------|----------------|--------|
| **Grid Risk Predictor** | Forecast next week’s risk per cell | XGBoost (Regression) | Historical weather, AQI, traffic, claims, season, day‑of‑week | Predicted risk (0‑1) for next 7 days |
| **Income Predictor** | Estimate worker’s expected earnings | Gradient Boosting (Regression) | Worker’s historical earnings by day/time, location, weather | Expected earnings (₹) for next hour/day |
| **Premium Calculator** | Personalize weekly premium | Weighted formula + ML‑adjusted weights | Grid history (last 4 weeks) + forecast + chosen plan | Weekly premium (₹) |
| **Fraud Detector** | 5‑layer anomaly detection + anti‑spoofing | Isolation Forest + Graph Neural Network | Claims, GPS trails, device sensors, social connections | Trust Score (0‑100), fraud flags |

**Training Data:** Synthetic dataset built from public weather records, mock claims, and worker behavior patterns (aligned with typical gig worker profiles). All data anonymized.

**ML Ops:** Models retrained weekly using fresh data, deployed via Flask microservices with REST APIs.

---

## Fraud Detection – 5‑Layer AI Fortress

We don't just say "we detect fraud" – we have **5 concrete layers** of AI‑powered verification:

| Layer | Method | Description | Example |
|-------|--------|-------------|---------|
| 1 | GPS Consistency | Speed checks, cell tower triangulation | Validate GPS authenticity | Claim from Andheri but GPS shows home for 6h → Flag |
| 2 | Grid‑Location Verification | Claim location must match cell risk at that time | Cross‑reference with grid risk | Claim for flood but cell risk was 0.2 → Flag |
| 3 | Behavioral Biometrics | Claim timing vs worker's normal pattern | Detect unusual behavior | Worker usually claims next day, now claims instantly → Flag |
| 4 | Device Fingerprinting | Same device ID, multiple accounts | Identify fraud rings | 3 claims from same device ID → Flag |
| 5 | Social Graph Analysis | Connected accounts colluding | Graph Neural Network | 5 workers at same location, same time → Flag |

---

## Adversarial Defense & Anti-Spoofing Strategy

> *Simple GPS verification is officially obsolete. We must outsmart coordinated fraud rings.*

### The Threat
A syndicate of 500 workers, using Telegram coordination and advanced GPS-spoofing apps, fake red-zone locations to trigger mass false payouts. They exploit parametric insurance platforms.

### Our Multi‑Modal Defense System
We fuse **14+ passive signals** into a **Trust Score** – distinguishing genuine stranded workers from spoofing rings without adding friction for honest users.

| Signal | Genuine Worker | Spoofing Fraudster |
|--------|----------------|-------------------|
| **GPS + Cell Towers** | Consistent with tower handoffs | GPS jumps; towers don’t match |
| **Wi‑Fi Fingerprint** | Sees real nearby BSSIDs (cafés, homes) | Spoofed area lacks matching Wi‑Fi |
| **Bluetooth Beacons** | Detects other devices, fixed beacons | Empty or synthetic environment |
| **Accelerometer/Gyroscope** | Micro‑movements (walking, pocket friction) | Static or perfectly periodic (bot‑like) |
| **Magnetometer** | Natural fluctuations (earth’s field) | Unnaturally stable or noisy |
| **Ambient Light Sensor** | Varies with time of day, weather | Constant or unrealistic |
| **Barometer** | Altitude changes with movement | Static or random |
| **Network Latency** | Ping times consistent with location | VPN/proxy introduces anomalies |
| **Battery Drain Rate** | Normal usage pattern | Often higher due to continuous spoofing |
| **App Interaction** | Tap patterns, typing speed, scrolling | Repetitive, inhumanly fast |
| **Historical Behavior** | Regularly works in that grid at that time | First‑time claim in that area |
| **Peer Context** | Other genuine workers nearby | Only syndicate members claim same spot |
| **Device Integrity** | No mock location apps, SafetyNet pass | Emulator, root, or mock location enabled |

### Trust Score & Workflow
- **Score ≥ 70**: Auto‑approve (instant payout).
- **Score 30–69**: Step‑up verification (passive re-scan, OTP, quick voice call).
- **Score < 30**: Auto‑reject + account lock + admin alert.

### Syndicate Detection Engine
- **Graph Neural Network** on co‑claim and device‑sharing graphs to detect tightly connected subgraphs (potential rings).
- **Time‑series clustering** of claim timestamps to find synchronized attacks.
- **Anomaly detection** (Isolation Forest) on aggregated features (e.g., 500 claims from same synthetic location within 10 minutes).

### UX Balance – No Honest Worker Left Behind
- Passive re-scan: App automatically recollects sensor data after 30 seconds – no user action.
- Selfie with live timestamp: AI checks liveness and geotag (10 seconds).
- OTP via SMS: Confirms active SIM in area (5 seconds).
- Appeal mechanism: Flagged workers can upload evidence; if genuine, get retroactive payout + ₹50 apology bonus.

---

## Tech Stack & Architecture

| Layer | Technology | Why |
|-------|------------|-----|
| **Frontend (Mobile)** | React Native, Mapbox GL | Cross‑platform, beautiful maps, real‑time updates |
| **Frontend (Admin)** | React.js, Chart.js | Responsive dashboard, interactive charts |
| **Backend** | Node.js + Express | Lightning‑fast API, easy integration with ML microservices |
| **Database** | MongoDB | Flexible schema for adaptive grids, geospatial queries (2dsphere indexes) |
| **AI/ML** | Python + Flask, Scikit‑learn, XGBoost, PyTorch Geometric (GNN) | Rich ML ecosystem, easy deployment |
| **APIs** | OpenWeatherMap, WAQI, NewsAPI, Google Maps (mock), Razorpay (mock) | Free tiers available, meets integration requirements |
| **Anti‑Spoofing** | Google Play Integrity, SafetyNet, custom sensor fusion library | Device integrity and environmental fingerprinting |
| **DevOps** | GitHub Actions, Docker | CI/CD for smooth development |

---

## 6‑Week Development Roadmap

### Phase 1 (Weeks 1‑2) – Ideation & Foundation (Due March 20)
- [x] Persona research (Arjun, Sunita, Ramesh) – emotional stories documented.
- [x] Adaptive grid system designed (quadtree).
- [x] Weekly pricing algorithm finalized.
- [x] Tech stack selected.
- [x] UI wireframes (Figma) – in progress.
- [x] 2‑min strategy video – in progress.
- [x] GitHub repo with this README.

### Phase 2 (Weeks 3‑4) – Automation & Protection
- [ ] Build worker registration (React Native).
- [ ] Implement adaptive grid risk API (Node.js + quadtree).
- [ ] Integrate weather APIs for 3 triggers.
- [ ] Create weekly premium calculator (Python).
- [ ] Develop basic claims system (MongoDB).
- [ ] **Deliverable:** 2‑min demo video + executable code.

### Phase 3 (Weeks 5‑6) – Scale & Optimise
- [ ] Implement 5‑layer fraud detection + anti‑spoofing.
- [ ] Add mock payment gateway (Razorpay).
- [ ] Build admin dashboard with adaptive grid heatmap.
- [ ] Train ML models on synthetic data (including fraud scenarios).
- [ ] Record 5‑min final demo video.
- [ ] Prepare final pitch deck (PDF).
- [ ] **Deliverable:** Final code + pitch deck + video.

---

## Team

| Name | Role | Responsibilities |
|------|------|------------------|
| Asmit Vedant | Backend | Node.js, MongoDB, API integration, grid engine |
| Dharshini Praveen Kumar | Frontend | React Native, Mapbox GL, UI/UX design |
| Tamizarasi S | AI/ML | XGBoost, Gradient Boosting, ML model development |
| G Varshaa | AI/ML | Isolation Forest, Graph Neural Networks, fraud detection |
| Thota Jahanvi | Frontend | React Native, admin dashboard, video production |

---

## Links & Resources

- **GitHub Repository:** [https://github.com/your-team/earnguard-ai](https://github.com/your-team/earnguard-ai)
- **Phase 1 Demo Video:** [YouTube/Google Drive Link]
- **Figma Designs:** [Figma Link]
- **Team Contact:** [Discord/WhatsApp group link]

---

##  Compliance Matrix

| Requirement | Our Approach |
|------------|-------------|
| Weekly Pricing | Personalized weekly premium based on risk |
| Income Loss Only | Payouts tied to disruption-based income loss |
| AI Risk Assessment | XGBoost + ML-based grid prediction |
| Fraud Detection | 5-layer AI + anti-spoofing |
| Parametric Automation | Real-time triggers + instant payouts |
| API Integration | Weather, AQI, Maps, Payments |



---

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
  <img src="https://img.shields.io/badge/contributors-5-blue" />
  <img src="https://img.shields.io/badge/Guidewire-DEVTrails%202026-ff69b4" />
</p>

