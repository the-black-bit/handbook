# Prodcut Specification

Following the discovery phase, customer needs are expressed subjectively.

Specifications are descriptions of what the product must achieve i.e. targets for product development.
- Precise and unambiguous
- Measurable
- Key questions and trade-offs between different product characteristics.
- Set early in development but undergo multiple revisions throughout development.

Types of Specifications
- Product Specifications: Precise descriptions of what the product must do.
- Product Requirements: Used interchangeably by different teams.
- Design Variables: Environment Variables/Feature flags.

For complex products, specifications are established twice:
- Target Specifications: Early Ambitious goals the development team believes will meet market demands based on initial customer needs.
- Final Specifications: Defined post-concept selection, adjusted based on technological constraints and cost considerations.

## Establishing Target Specifications:

### 1. Prepare the List of Metrics:
   - Metrics directly reflect how well the product satisfies each need.
   - Ideally 1 to 1, often many to many.
   - Example: Ease of installation metric could be installation time, though this translation isn't always straightforward due to nuanced customer needs.

Needs-Metrics Matrix is a nice visualization used in Quality Function Deployment (QFD) to prioritize specifications.

#### Guidelines for Metrics:
- **Completeness:** Ideally, each need should have a corresponding metric.
- **Dependency:** Metrics should be dependent variables, reflecting overall product performance. For example, the length of the car is not a dependent variable. We should allow the designers to have flexibility with independent variables to satisfy dependent variables.
  - Metrics should focus on the outcomes that matter to customers and stakeholders, not the specific design choices used to achieve those outcomes. This ensures the design process remains flexible and innovative.
- **Practicality:** Metrics should be measurable with accessible tools or methods.
- **Subjective Metrics:** Some needs (e.g., "instills pride") are subjective and may not have quantifiable metrics, labeled as "Subj."
- **Consider industry standards and media evaluation criteria:**
  - Industry Standards:
    - Resolution and Bitrate of video
    - Latency and buffering of streaming
    - Geographic coverage of CDN
  - Media Evaluation Criteria: The specific metrics or tests used by journalists, reviewers, or industry publications to assess and compare products.
    - Ease of navigation
    - Number of items/genres
    - Google lighthouse

#### Importance Rating:
- Derived from importance ratings of corresponding needs.
- Importance ratings determined through team discussion rather than formal algorithms, with conjoint analysis used for critical decisions.

### 2. Collect Competitive Benchmarking Information according to the prepared metrics:
   - Understand industry standards.
   - Benchmark competitor performance.
   - Alternative Approach: Compares how well competitor product satisfies customer needs.

### 3. Set Ideal and Marginally Acceptable Target Values:
   - Ideal targets are ambitious goals representing top performance.
   - Marginally acceptable targets ensure the product remains viable.

### 4. Reflect on Results and Process:
   - Evaluate the feasibility of selected metrics and target values.
   - Ensure alignment with customer needs and competitive benchmarks.

## Setting the Final Specifications
1. Develop Technical Models of the Product
- Predict technical feasibility and product performance without extensive physical testing.
2. Develop a Cost Model of the Product
- Estimate manufacturing costs
3. Refine the Specifications, Making Trade-Offs Where Necessary
- Adjust target specifications based on the above.
4. Flow Down the Specifications as Appropriate
- Cascade product specifications to subsystems or components.
  - Aligns subsystem development with overall product goals.
  - Ensures consistency across different components.

### Step 5: Reflect on the Results and the Process
- Customer needs
- Competitive positioning
- Profitability targets

## Trade-off analysis that is balancing competing objectives or metrics is one of the important activities throughout this process
  - Competitive maps: Smart Positioning
  - Cost-performance models: How changes in design decisions affect both the performance metrics and the cost of development.
  - Sometimes poor performance on one specification can be compensated by high performance on others but there is often a threshold the performance below which is deemed unacceptable regardless of performance in other areas.

Several metrics are often involved in trade-offs in software development:

1. **Cost**:
   - **Development Cost**: The expenses associated with developing the software, including salaries for developers, licensing fees, and infrastructure costs.
   - **Operational Cost**: Ongoing costs for running the software, such as cloud services, maintenance, and customer support.

2. **Performance**:
   - **Speed/Latency**: The responsiveness of the software, often measured in milliseconds. Important for user satisfaction and overall performance.
   - **Throughput**: The amount of data processed in a given time period, relevant for databases and data-intensive applications.

3. **Scalability**:
   - **Horizontal Scalability**: The ability to add more machines or nodes to handle increased load.
   - **Vertical Scalability**: The ability to add more resources (CPU, memory) to a single machine to handle increased load.

4. **Reliability**:
   - **Uptime**: The percentage of time the software is operational and available to users. Typically measured in terms of "nines" (e.g., 99.9% uptime).
   - **Mean Time Between Failures (MTBF)**: The average time between failures, indicating the reliability of the software.

5. **Security**:
   - **Vulnerability Detection**: The number and severity of vulnerabilities found and fixed over time.
   - **Data Breach Incidents**: The frequency and impact of data breaches or security incidents.

6. **Usability**:
   - **User Satisfaction**: Often measured through surveys and Net Promoter Scores (NPS).
   - **User Retention Rate**: The percentage of users who continue to use the software over time.

7. **Flexibility**:
   - **Customizability**: The extent to which the software can be tailored to meet different user needs or integrated with other systems.
   - **Extensibility**: The ease with which new features can be added to the software.

8. **Maintainability**:
   - **Code Quality**: Measured by metrics such as cyclomatic complexity, code churn, and the number of code smells.
   - **Time to Resolve Issues**: The average time taken to fix bugs or implement changes.

9. **User Experience (UX)**:
   - **Load Time**: How quickly the software or platform loads for users.
   - **Ease of Navigation**: Measured by user testing and feedback on how easily users can find what they need.

10. **Interoperability**:
    - **API Availability and Quality**: The number and quality of APIs available for integration with other systems.
    - **Standards Compliance**: Adherence to industry standards and protocols for data exchange and interoperability.
