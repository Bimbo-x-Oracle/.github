# 🧠 Panquímetro: Genetic Algorithm Optimization for Logistics

**Panquímetro** is a logistics optimization system developed for Bimbo to enhance the unloading process in distribution yards using genetic algorithms. The system prioritizes truck unloading based on demand fulfillment, product importance, and available operational resources, leading to reduced wait times, minimized operational costs, and improved customer satisfaction.

## 🚀 Project Objective

To automate the truck unloading sequence at Bimbo's logistics yard by implementing a **genetic algorithm** that assigns trucks to unloading bays based on:

- Demand satisfaction
- Strategic product importance
- Truck arrival and wait times
- Operational bay constraints

## 🧬 Why Genetic Algorithms?

The complexity and variability of truck assignments make traditional scheduling inefficient. Genetic algorithms allow us to:

- Explore large solution spaces efficiently
- Adapt to real-time logistics changes
- Handle multiple constraints (priority, timing, bay capacity)
- Avoid suboptimal solutions via mutation and crossover

## 📊 Key Features

- **Data preprocessing** of truck and order sheets
- **Custom fitness function** balancing demand fulfillment and operational time
- **Partially mapped crossover** and **swap mutation**
- **Parameter tuning** for crossover/mutation rates and population size
- **Statistical analysis** to compare configurations

## ⚙️ Tech Stack

- **Python** (core algorithm)
- **Pandas** for data processing
- **Sklearn (MinMaxScaler)** for fitness normalization
- **Jupyter Notebook** for experimentation and visualization

## 📈 Best Performing Configuration

| Parameter           | Value         |
|--------------------|---------------|
| Crossover Type      | Partially Mapped (PMX) |
| Mutation Type       | Swap Mutation |
| Crossover Rate      | 85%           |
| Mutation Rate       | 15%           |
| Population Size     | 150           |
| Generations         | 300           |

## 📌 Benefits for Bimbo

- ⏱️ Faster unloading processes
- 📦 Improved demand alignment
- 💸 Reduced operational costs
- 🤖 Fewer human errors through automation
- 📈 Scalable and adaptable to market changes
