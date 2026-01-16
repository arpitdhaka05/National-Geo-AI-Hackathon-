# 🌍 National GeoAI Hackathon — AI-Powered Drainage Planning System  
### Team Protego

An AI-driven geospatial intelligence system that transforms SVAMITVA drone data into engineering-grade drainage designs to prevent annual monsoon flooding in Uttar Pradesh villages.

---

## 👥 Team Details

**Team Name:** Protego  
**Members:**  
- Arpit Dhaka (Team Lead)  
- Aditi Hirkude  

---

## 🚨 Problem Statement — The Urgent Crisis

Every monsoon, Uttar Pradesh faces devastating floods due to poor rural drainage infrastructure.

- 700+ villages affected annually across 17 districts  
- 1,137 lives lost in 5 years  
- Thousands of hectares of agricultural land submerged  
- Recurring losses worth crores every year  

Meanwhile, India’s **SVAMITVA Mission** has already mapped 90,000+ villages using drones, generating high-resolution topographic data.

Our mission is to convert this raw data into actionable drainage designs using AI.

---

## 💡 Our Solution — From Data to Drainage Design

We built a 4-Step AI Pipeline that converts raw drone survey data into construction-ready drainage plans.

### 🔹 Step 1 — Ground Classification
- Input: 77M+ drone LiDAR points (~5 cm accuracy)
- AI separates bare earth, buildings, trees, roads, and vehicles  
- Output: Pure terrain model

---

### 🔹 Step 2 — Precision DTM Generation
- Builds a Digital Terrain Model (DTM)
- Engineering-grade surface accuracy  
- Validated at **0.60 m RMSE**

---

### 🔹 Step 3 — Hydrological Diagnosis
- Detects natural flow paths, accumulation zones, and blockages  
- Identifies why and where waterlogging occurs  

---

### 🔹 Step 4 — Optimized Drainage Design
- Auto-generates terrain-aware drainage channels  
- Produces L-sections and Earthwork BOQ  
- Output: Construction-ready drainage blueprint  

---

## 📍 Case Study — Village Pure, Uttar Pradesh

- 15% of village identified as flood-prone  
- 254,050 grid cells marked as high-risk  
- 1,432 drainage intervention points  
  - High Priority: 435  
  - Medium Priority: 567  
  - Low Priority: 430  

Targeted drainage prevents residential flooding, crop destruction, and road damage.

---

## 📊 Accuracy Validation

- RMSE = 0.60 meters  
- Perfect spatial alignment with village boundaries  
- Natural slopes and man-made structures match ground truth  
- Sufficient for drainage channel design and BOQ preparation  

---

## 💰 Cost & Scale Model

### Cost per Village
**₹14.3 Lakhs per village**

Breakdown:
- Engineering Design — 65%  
- Data Processing — 25%  
- Validation & BOQ — 10%  

### ROI Logic
- One-time investment: ₹14.3 Lakhs  
- Annual flood losses: Crores  
- Prevention is far cheaper than recovery

---

## 🚀 Scalable Vision for Uttar Pradesh

- 90,573 villages already mapped under SVAMITVA  
- No new surveys required  
- Immediate deployment possible  

### Proposed Pilot
- 10 high-risk districts  
- 100 villages (Phase 1)  
- Target districts: Ballia, Varanasi, Gorakhpur  

---

## 🗺️ 14-Month Execution Roadmap

### Phase 1 (Months 1–3): High-Priority Safety
- Protect residential zones  
- Construct 435 critical drains  
- Clear major blockages  

### Phase 2 (Months 4–8): Agricultural Resilience
- Field drainage networks  
- Grass waterways  
- Canal-field connectivity  

### Phase 3 (Months 9–14): System Completion
- Final network connections  
- O&M protocols  
- Handover to Gram Panchayat  

---

## 🏆 Why Our Model Wins

| Traditional Projects | Our AI Model |
|--------------------|--------------|
New surveys required | Uses existing SVAMITVA data |
Static reports | Construction-ready BOQ & plans |
Unvalidated accuracy | Field-validated 0.60m RMSE |
Generic algorithms | Terrain-aware hydrology |
One-off demos | Proven multi-village pipeline |

---

## 📄 Full Project Proposal

Download the complete proposal here:  
**[Proposal.pdf](./Proposal.pdf)**

---

## 🛠 Suggested Repository Structure
geoai-drainage-planning
│

├── data/ # Drone / LiDAR inputs

├── notebooks/ # AI pipeline implementation

├── models/ # Terrain & hydrology models

├── outputs/ # DTM, flood maps, drainage plans

├── Proposal.pdf

└── README.md


---

## 📜 License
This project is developed for the **National GeoAI Hackathon** under Team Protego.


