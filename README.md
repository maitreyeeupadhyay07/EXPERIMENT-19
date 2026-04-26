
# 📊 Experiment 19: Real-World and Interactive Visualizations

---

## 🎯 Aim

To study and implement real-world and interactive visualization techniques using Python libraries such as Plotly, Matplotlib, Pandas, NumPy, SciPy, and Matplotlib-Venn for representing hierarchical data, clustering, set relationships, flow systems, multi-variable analysis, and performance comparisons.

---

## 📚 Theory

Data visualization plays a crucial role in modern data analysis. While simple charts like bar graphs and line plots are useful for basic comparisons, real-world problems often demand more advanced visualization techniques capable of representing hierarchy, relationships, clustering, movement, and multi-dimensional data.

Interactive visualizations enhance data analysis by enabling users to:

* Hover over data points
* Zoom in and out
* Rotate 3D plots
* Filter data dynamically
* Explore patterns in greater depth

This experiment focuses on advanced and interactive visualization methods widely used in business dashboards, machine learning, finance, education, and management analytics.

The libraries used include:

* **Plotly Express** → Simplified creation of interactive charts
* **Plotly Graph Objects** → Advanced and customizable visualizations
* **Matplotlib** → Static plotting library
* **Pandas** → Data handling and tabular structures
* **NumPy** → Numerical computations and data generation
* **SciPy** → Hierarchical clustering techniques
* **Matplotlib-Venn** → Creation of Venn diagrams

---

## 🔹 1. Treemap

A Treemap is used to represent hierarchical data through nested rectangles, where each rectangle corresponds to a category and its size reflects a numerical value.

In this example, departmental budget allocation was visualized:

* HR
* IT
* Sales
* Marketing

The chart was created using `px.treemap()`.

Parameters used:

* `path=` → Defines hierarchical structure
* `values=` → Determines the size of rectangles

Larger rectangles indicate higher budget allocation.

### Real-World Applications

* Budget distribution in organizations
* Sales categorization
* Investment portfolio analysis
* Storage utilization

Treemaps are especially useful when comparing multiple categories within limited space.

---

## 🔹 2. Dendrogram

A Dendrogram is a tree-like diagram used in hierarchical clustering.

It illustrates how data points group together step-by-step based on similarity. The vertical axis represents the distance or dissimilarity between clusters.

Functions used:

* `linkage(data, method='ward')` → Performs clustering
* `dendrogram()` → Visualizes cluster hierarchy

The Ward method minimizes variance within clusters.

### Real-World Applications

* Customer segmentation
* Genetic data analysis
* Pattern recognition
* Recommendation systems
* Image classification

Dendrograms are widely used in unsupervised machine learning.

---

## 🔹 3. Venn Diagram

A Venn Diagram visually represents relationships between sets using overlapping circles.

Example sets:

* Set A = {1,2,3,4}
* Set B = {3,4,5,6}

It shows:

* Elements unique to Set A
* Elements common to both sets
* Elements unique to Set B

The diagram was created using `venn2()`.

### Real-World Applications

* Database operations
* Probability and set theory
* Skill overlap analysis
* Market segmentation

Venn diagrams simplify understanding of set relationships.

---

## 🔹 4. Sankey Diagram

A Sankey Diagram represents flow from one stage to another.

The example illustrated student progression:

* Admission
* First Year
* Second Year
* Placement

Flow data:

* 100 students entered admission
* 80 continued further
* 60 reached placement

The diagram was created using `go.Sankey()`.

In Sankey diagrams, link thickness represents the quantity of flow.

### Real-World Applications

* Student retention tracking
* Supply chain processes
* Energy distribution
* Budget allocation flow
* Website user journey tracking

Sankey diagrams effectively highlight flow, loss, and transitions.

---

## 🔹 5. 3D Scatter Plot

A 3D Scatter Plot is used to visualize three numerical variables simultaneously.

Dataset variables:

* Study Hours
* Marks
* Attendance

Axes representation:

* X-axis → Study Hours
* Y-axis → Marks
* Z-axis → Attendance

The plot was created using `px.scatter_3d()`.

Plotly’s interactivity allows users to rotate and examine the plot from different perspectives.

### Real-World Applications

* Academic performance analysis
* Scientific data visualization
* Quality control in production
* Financial modeling

This visualization helps uncover patterns not easily visible in 2D charts.

---

## 🔹 6. Radar Chart

A Radar Chart (also known as a Spider Chart) is used to compare multiple variables along radial axes.

The example evaluated different skills:

* Python
* Machine Learning
* DBMS
* DSA
* Communication

The chart was created using `go.Scatterpolar()`.

Parameter used:

* `fill='toself'` → Fills the enclosed polygon

### Real-World Applications

* Skill evaluation
* Employee performance reviews
* Product comparisons
* Sports analytics

Radar charts clearly display strengths and weaknesses.

---

## 🔹 7. Importance of Interactive Visualization using Plotly

Unlike static charts, Plotly provides interactive features such as:

* Hover information
* Zooming capability
* Panning and rotation
* Interactive legends
* Enhanced visual presentation

These features make Plotly highly suitable for dashboards and professional reporting.

---

## 📊 Output Summary

The following visualizations were successfully created:

* Treemap
* Dendrogram
* Venn Diagram
* Sankey Diagram
* 3D Scatter Plot
* Radar Chart

---

## 📈 Comparison of Visualization Types

| Visualization Type | Main Purpose                |
| ------------------ | --------------------------- |
| Treemap            | Hierarchical comparison     |
| Dendrogram         | Cluster analysis            |
| Venn Diagram       | Set relationships           |
| Sankey Diagram     | Flow analysis               |
| 3D Scatter Plot    | Three-variable relationship |
| Radar Chart        | Multi-metric comparison     |
---

## ✅ Conclusion

This experiment successfully demonstrated various real-world and interactive visualization techniques using Python. Tools such as Treemap, Dendrogram, Venn Diagram, Sankey Diagram, 3D Scatter Plot, and Radar Chart were implemented using Plotly, Matplotlib, SciPy, and Pandas. These visualization methods are highly useful in analytics, business intelligence, machine learning, education, and decision-making systems where complex data needs to be presented clearly and effectively.

---

