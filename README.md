# Fractional Knapsack Simulator

An interactive web-based visualization tool for the Fractional Knapsack algorithm, demonstrating optimal resource allocation in computer science.

![image](https://github.com/user-attachments/assets/e885740f-079a-446d-b426-b06d121ae8a0)

---

## Key Features

- **Interactive Controls**: Dynamically add items with custom weights and profits.
- **Multiple Selection Strategies**:
  - Profit-to-Weight Ratio (Optimal Solution)
  - Highest Profit First
  - Lightest Weight First
- **Visual Feedback**: Real-time 3D knapsack rendering and capacity metrics.
- **Comparative Analysis**: Detailed results table showing fractional selections.

![image](https://github.com/user-attachments/assets/1b505843-c5c4-49af-8a8f-d153455fd33a)

---

## Usage Instructions

### 1. Setup
1. Download the repository or copy `index.html`
2. Open the file in any modern browser (Chrome, Firefox, Edge)

### 2. Running a Simulation
1. **Add Items**:
   - Enter item details (Name, Weight, Profit)
   - Click "Add Item" to populate the list

2. **Configure Parameters**:
   - Set knapsack capacity (e.g., 15 kg)
   - Select a packing strategy

3. **Execute**:
   - Click "Run Simulation" to view results
   - Observe the packing sequence in the 3D view

### 3. Interpreting Results
- **Visualization Area**: Shows items packed with color-coded proportions
- **Metrics Panel**: Displays total profit and capacity utilization
- **Results Table**: Lists exact fractions and profit contributions

![image](https://github.com/user-attachments/assets/4d8e507e-0d80-4e61-baaf-2e6c983fb1d3)

---

## Technical Implementation

- **Algorithm**: Greedy method with O(n log n) sorting complexity
- **Frontend**: Vanilla JavaScript with Bootstrap 5 for responsive layout
- **Visualization**: CSS 3D transforms for knapsack rendering
- **Compatibility**: Cross-browser support (no external dependencies)

---

## Educational Applications

This tool helps demonstrate:
1. The efficiency of greedy algorithms for fractional problems
2. Why profit-to-weight ratio yields optimal solutions
3. Tradeoffs between different selection strategies
4. Practical applications in resource allocation
