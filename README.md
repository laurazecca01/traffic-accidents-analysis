# Road Accident Analysis and Safety Routing Visualization for London 🚖

This project explored road accident data in London to develop insights for a potential **Google Maps safety routing feature**. By analyzing accident hotspots, traffic data, and network mapping, we aim to identify high-risk areas and provide optimized routing to enhance safety. The data used for this project was sourced from Kaggle and the UK Department for Transport.
This was a group project from university, I worked indivudally on the slides and 1/3 graphs, traffic incidents as a network object (RFQ1 in the html).
The goal of this project was to leverage data visualization and spatial analysis techniques to understand patterns in road accidents across London. The insights can guide the development of safer routing options by highlighting accident-prone areas and understanding their causes.

This analysis combines:
- Accident severity data
- Traffic volume data
- Road network mapping

## Research Questions

### 1. **Where are the most frequent road accident locations in the city?** (RFQ1)
We identify hotspots for accidents and analyze their severity distribution (Slight, Serious, Fatal). This helps prioritize areas requiring safety interventions.

### 2. **What is the relationship between traffic volume and accidents?**
To explore whether accidents are driven by traffic volume or other factors, we integrate traffic data and compare it with accident density.

### 3. **How can network analysis improve routing for safety?**
We use the London street network to visualize high-risk areas and discuss its potential for simulating optimized safety routing.

---

## Key Visualizations

### **Traffic Density and Accident Hotspots**
Heatmaps compare traffic volume and accident density, highlighting a correlation in Central London and anomalies in East London.
### **London Street Network with Accident Data**
A mapped network graph displaying accident hotspots on London’s road network, providing a foundation for routing optimization.  
![Network Map](visualizations/london_road_network.png)

---

## Findings

1. **Accident Severity**: The majority of accidents are Slight, but Serious and Fatal accidents are concentrated in specific areas like the city center.
2. **Traffic Correlation**: While traffic volume explains many accident hotspots, anomalies like East London suggest other contributing factors.
3. **Network Insights**: Mapping the street network reveals potential for routing optimization to avoid high-risk areas.

---

### Data Sources
- **Road Accident Data**: [Kaggle Dataset](https://www.kaggle.com/)
- **Traffic Data**: [UK Department for Transport](https://roadtraffic.dft.gov.uk/regions/6)

### Tools and Libraries
- **Visualization**: Plotly, Matplotlib, Seaborn
- **Geospatial Analysis**: GeoPandas, OSMnx, Folium
- **Data Processing**: Pandas, NumPy
- **Network Analysis**: NetworkX
