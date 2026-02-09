# Airport Traffic Simulation Model

## Project Overview
This project presents a **simulation-based model for airport traffic management**, designed to analyze passenger flow, service efficiency, and resource utilization within an airport environment. The model applies **queueing theory and discrete-event simulation** to evaluate performance and support decision-making for airport operations.

Although the solution is currently a conceptual model, simulation results demonstrate its potential effectiveness and feasibility for real-world implementation.

---

## Team Members
- Rama Alassi  
- Mohamed Awad  
- Charbel Charbachi  
- Charbel Farhat  
- Mohamad Ismail  

---

## The Big Idea
Airports require massive investments and highly efficient operations to handle increasing passenger volumes. Our model aims to **optimize airport traffic flow**, reduce congestion, and improve passenger experience while maintaining operational efficiency.

---

## Why This Project?
- The estimated cost to open an airport can reach **$400 million**
- Inefficient passenger flow leads to delays, dissatisfaction, and increased costs
- Simulation allows testing improvements **without disrupting real operations**

---

## Airport Services Modeled
- Entrance & passenger arrival
- Check-in counters
- Border control
- Security screening
- General security
- Boarding gates
- Duty-free areas
- Airport security (Darak & Internal Security)

---

## Key Performance Indicators (KPIs)
The simulation evaluates performance using the following KPIs:
- Average check-in time
- Average security screening time
- Flight on-time performance
- Passenger throughput
- Queue length and waiting time
- Passenger satisfaction
- Staff efficiency
- Baggage handling time
- Peak-hour passenger load

---

## Model Parameters

### Passenger Flow
- **Arrival rate:** 10 passengers per minute

### Check-In
- Capacity: 20 counters  
- Time delay: 3 minutes  

### Border Control
- Capacity: 100  
- Time delay: Triangular (0.5, 1, 1.5) minutes  

### Security Screening
- Capacity: 20  
- Time delay: Triangular (5, 5, 15) minutes  

### General Security
- Capacity: 20  
- Time delay: Triangular (5, 10, 15) minutes  

---

## Methodology
The model applies **queueing theory** to assess system efficiency and congestion levels:

- Arrival rate (λ)
- Service rate (μ = 1 / 3)
- Number of service resources (c)

Queueing performance is evaluated using established theoretical foundations.

**Reference:**  
Lipsky, L. (2006). *Queueing Theory: A Linear Algebraic Approach*. Springer Science & Business Media.

---

## Cost Analysis
- Estimated cost of extending resources:  
  **$220,000 per year**

Simulation allows evaluating whether such investments improve performance before committing resources.

---

## Stakeholders
- Lebanese citizens
- Lebanese tourism sector
- Airport employees
- Lebanese economy

---

##  Limitations
- Government approval requirements
- Funding and financial constraints
- Technological and infrastructure limitations

---

## Conclusion
While this solution currently exists as a conceptual model, simulation results demonstrate its **effectiveness and practicality**. The next step is transitioning from simulation to **real-world implementation**, enabling improved airport efficiency, passenger satisfaction, and economic impact.

## 🔗 Project Resources
- Presentation: *AirportSimulationModel-Presentation*
