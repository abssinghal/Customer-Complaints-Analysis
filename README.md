Problem Statement

Traditional dashboards often rely heavily on filters, duplicated worksheets, or multiple views to answer related analytical questions. This increases uncessary complexity and can negatively impact performance. The objective here was to architect a single dashboard that dynamically adapts based on user input while maintaining clarity and efficiency.

Solution Architecture

The dashboard is powered by parameters that control:

- Metric switching
- Dimension and perspective toggling

Instead of creating separate worksheets for each analytical variation, calculated fields were designed to respond dynamically to parameter values. This enables one visualization framework to support multiple analytical scenarios without redundancy.

Data preparation involved:

- Cleaning and standardizing fields across both datasets
- Aligning data types and hierarchies for consistency
- Designing logical relationships to enable seamless cross-visual interaction
- Validating aggregation levels across time and geographic dimensions

Visualization Strategy

Each chart type was selected based on analytical intent:

- Bar Charts → categorical comparison and ranking
- Line Charts → trend and time-series analysis
- Maps → geographic distribution and spatial insights
- Tile → high-level metric monitoring
- Trend Lines → directional and statistical context

All worksheets are interconnected and respond to parameter changes, ensuring a responsive and interactive user experience without requiring multiple sheets/dashboards.

Key Takeaway

A well-architected dashboard streamlines the path from query to insight. This dashboard demonstrates an approach focused on flexibility, scalability, and interactive analytics within Tableau.

The interactive dashboard is accessible at: [Insert Dashboard Link]
