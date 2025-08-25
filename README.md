# 🚍 Automating Employee Transport Routing with Python + ML

## 🌟 Introduction
Employee transport routing isn’t just shortest paths — it’s a **daily optimization puzzle** balancing:
- **Cost efficiency**, 
- **Safety & compliance** (escort provisions, restricted roads), 
- **Employee comfort** (medical cases, fair travel times).

I built an **end-to-end routing engine in Python** that blends:
- **Engineered zone framework** (my custom zone coding that defines how areas can be clubbed),
- **Pattern learning** from historical supervisor trail clubbing,
- **Rule-based seater allocation** (12 → 6 → 4),
- **Validation & audit** (Folium maps),
- **ML experiments** (scikit-learn) to test whether supervisor patterns are learnable.

---

## 🛠️ Solution Design

1. **Engineered a zone framework** ✅  
   Backbone of routing — designed from 750+ nodal points across Bengaluru city to define feasible clubbing of areas.

2. **Pattern learning from supervisor trails** ✅  
   Learned historical clubbing to optimize tail routes and align with actual operations.

3. **Rule-based routing engine (Python)**  
   Sort by `Shift` + `IN/OUT` + `Zone` + `Distance`; allocate seaters 12 → 6 → 4; create predicted tripsheets.

4. **Validation & audit**  
   Checks: over-capacity, zone integrity, IN/OUT purity; Actual vs Predicted comparisons; Folium route maps.

5. **ML experiments**  
   KNN baseline showed that supervisor routing also depends on **operational constraints** (escort, medical, road rules) — the model framework is ready to incorporate these features.

---

## 📊 Results

- ~**90%** automation accuracy for employee-to-route assignment  
- ~**10%** of routes shaped by **operational discretion/constraints** (escort, medical, restricted roads, VIPs)  
- **Hybrid outcome:** **90% automation + 10% supervisor discretion = 100% operational feasibility**

---


### — Open in Colab
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hemanth282004/Employee-Transport_Routing/blob/main/Auto_Routing_Project.ipynb)


🏆 Achievements

- Engineered a zone framework (backbone of routing)

- Implemented pattern learning from supervisor trails

- Automated routing in Python (pandas, scikit-learn, folium)

- Built a full validation + audit workflow (Excel + maps)

- Quantified the operational discretion layer that complements automation
