Vendor Information: 
Name: TIDY
Website: https://www.tidy.com
Description: Tool to automate cleaning and maintenance.
Submission date: Feb 14, 2025

Score: 90% (71/79)
Summary: Good at documentation and proactive steps, bad at communication and edge case management. Effectively the opposite stength/weaknesses as humans.

## I. Property Understanding & Digital Twin

### A. Asset Tracking
- [x] Maintain a real-time log of fixed assets with status tracking (e.g., dishwasher needs repair, HVAC filter at 80% capacity)
- [ ] Monitor usage hours and predict maintenance needs (e.g., schedule dishwasher maintenance after 1000 cycles)
- [ ] Document detailed asset specifications including model numbers, warranty details, and property features (e.g., 3 bedroom, 2000 sq ft, 2 HVAC units)

### B. Inventory Management
- [x] Monitor cleaning supply levels thresholds (e.g., paper towels, disinfectants)
- [x] Predict usage based on property data (square footage, rooms, surface types) and usage patterns (guest/tenant count)
- [x] Set up automated replenishment orders with vendor-specific requirements through preferred channels
- [x] Send automated restock alerts to inventory managers when supplies drop below preset thresholds
- [x] Coordinate physical restocking of supplies to specific locations (e.g., owner's closet, cleaning rooms)
- [ ] Track consumable supply usage patterns by area and season for accurate forecasting
- [ ] Monitor lifecycle of cleaning equipment and schedule replacements before breakdown

### C. Property Mapping
- [ ] Maintain updated digital floor plans with room-specific cleaning requirements
- [ ] Document surface materials with specific cleaning protocols (e.g., marble floors require special cleaners)
- [ ] Map all access points with entry methods (e.g., garage code 1234, front door key in lockbox 5678)
- [x] Develop a comprehensive digital twin linking assets to specific locations (e.g., Washer #1 in basement utility room)

## II. Task & Requirements Management

### A. Scheduled Maintenance
- [x] Coordinate cleaning schedules with tenant move-in/move-out dates, considering specific property requirements and condition assessments
- [x] Dynamically adjust cleaning and maintenance schedules based on occupancy, crew availability, and real-time performance metrics
- [ ] Calculate ROI for preventative cleaning maintenance by tracking metrics such as issue frequency, cost savings from avoided re-cleans, and asset longevity improvements
- [x] Schedule HVAC filter changes based on manufacturer guidelines, air quality metrics, and occupancy patterns
- [x] Track appliance maintenance history and schedule servicing based on usage cycles, manufacturer recommendations, and performance data


### B. On-Demand Requests
- [x] Immediately route urgent cleaning tasks (e.g., water spill cleanup, biohazard decontamination) to vendors with available crews and the required specialized equipment
- [x] Match cleaning specialists to jobs based on required certifications and expertise (e.g., healthcare facility cleaning, high-rise window washing, carpet deep cleaning)
- [x] Handle last-minute cancellations by automatically triggering backup staffing protocols and adjusting affected cleaning schedules
- [x] Automatically re-optimize cleaning routes and schedules based on real-time service requests, geographic clustering of tasks, and crew proximity to optimize response times

### C. Emergency Response
- [ ] Develop detailed emergency cleaning and maintenance protocols for incidents such as severe water leaks, ensuring 24/7 response readiness
- [x] Route urgent facility cleaning issues to available technicians via their preferred method (SMS, call, or app alert) with specific incident details and required equipment
- [x] Assess if regular cleaning operations can continue in unaffected areas during emergency maintenance, with clear documentation of postponed zones
- [x] Dispatch emergency maintenance crews equipped for specific scenarios (e.g., plumbers, cleaners)

### D. Task List Management
- [x] Generate digital, location-specific checklists for cleaning tasks with step-by-step instructions (e.g., sanitizing high-touch surfaces in public areas)
- [x] Track cleaning crew progress in real-time
- [x] Enable incident reporting via photo/video submissions with automatic alert escalation for cleaning-related issues
- [x] Update task requirements based on changing conditions (e.g., surface types, occupancy patterns, seasonal needs)

### E. Vendor Guidelines
- [ ] Maintain and regularly update detailed cleaning protocols and vendor-specific work instructions, including specialized checklists for sanitization and high-risk maintenance tasks
- [x] Regularly update vendor qualifications by tracking required cleaning certifications (e.g., green cleaning, biohazard remediation) and compliance with local maintenance standards
- [x] Archive insurance certificates and compliance documents specific to cleaning and maintenance operations

### F. Safety & Environmental Requirements
- [ ] Continuously monitor and enforce compliance with safety guidelines (e.g., OSHA standards) and environmental regulations specific to waste disposal and chemical storage
- [ ] Maintain records of safety certifications for cleaning equipment (e.g., ladder safety, electrical safety) and promptly document any workplace safety incidents
- [ ] Track PPE requirements for specific cleaning tasks and enforce safety protocol adherence
- [ ] Update emergency procedures based on historical incidents reports and regulatory changes

### G. Risk Management
- [ ] Identify potential cleaning and maintenance risks—such as equipment malfunctions, chemical spills, or biohazard exposures—and proactively implement targeted preventive measures
- [ ] Evaluate risk levels based on facility-specific factors (e.g., high-traffic public areas versus private offices) and adjust cleaning protocols accordingly
- [ ] Track incident reports and generate detailed risk assessments specific to cleaning and maintenance operations

## III. Vendor Coordination

### A. Multi-Channel Communication
- [x] Manage vendor communications via email, SMS, and phone
- [x] Support email coordination for vendors using digital communication
- [x] Enable SMS-based coordination for vendors who don't use apps/websites (primary channel)
- [x] Handle phone-based coordination for vendors preferring voice communication
- [x] Maintain detailed logs of all communications
- [x] Ensure messages trigger timely updates in the scheduling system

### B. Compliance Management
- [x] Verify vendor insurance and liability coverage
- [x] Track cleaning certifications and background screening statuses
- [x] Monitor adherence to local licensing and regulatory requirements

### C. Equipment & Resource Verification
- [x] Verify vendor equipment availability and functionality prior to job assignments
- [ ] Monitor equipment maintenance status and resource allocation
- [x] Automatically reassign tasks if equipment malfunctions are reported

## IV. Job & Schedule Management

### A. Acceptance Prediction
- [x] Analyze historical data to predict job acceptance rates based on building type, certifications, and location
- [ ] Adjust job compensation based on complexity factors (e.g., biohazard cleanup, high-rise windows)
- [x] Increase compensation automatically for hard-to-serve scenarios (remote locations, holiday jobs, last-minute requests)
- [x] Factor in travel time and pay rate impact on acceptance probability

### B. Cancellation Risk Management
- [x] Predict cancellation likelihood and implement backup staffing protocols
- [x] Monitor last-minute cancellation triggers (e.g., sudden staff unavailability due to illness)

### C. Issue Prevention
- [x] Implement proactive measures to prevent service disruptions by cross-referencing crew availability, scheduled equipment maintenance, and real-time incident alerts
- [ ] Identify potential scheduling conflicts and equipment issues in advance through predictive analytics
- [x] Automatically reschedule affected cleaning tasks during emergencies or equipment failures with minimal service disruption

### D. Access Control
- [x] Manage electronic access for cleaning staff through integrated building access systems
- [x] Sync cleaning schedules with property access controls to ensure secure entry

## V. Quality Assurance

### A. Stakeholder Feedback
- [x] Collect post-service feedback through multiple channels (email, SMS, app) from all stakeholders
- [x] Track quality issues by category (cleanliness, timeliness, communication) and develop targeted improvement plans
- [x] Follow up automatically on low ratings
- [x] Automatically schedule re-cleans when quality metrics fall below acceptable standards

### B. Pro Communication
- [ ] Maintain communication channels with cleaning crews with response time SLAs of less than 1 minute for responses.
- [x] Escalate issues promptly in accordance with rules.
- [x] Archive detailed communication logs including timestamps, response times, and resolution details

### C. Visual Verification
- [x] Process before/after cleaning photos
- [x] Process before/after cleaning videos
- [x] Analyze / verify cleaning quality against specific standards (e.g., no visible dust, streak-free windows)
- [x] Archive visual records with metadata (timestamp, location, cleaner) for quality audits

## VI. Property Data Updates

### A. Maintenance Records
- [x] Document completed cleaning and maintenance tasks
- [x] Update maintenance histories with detailed service records and time logs
- [ ] Track service patterns to improve preventative maintenance and future scheduling

### B. Inventory Updates
- [x] Update stock levels based on usage data and automated restock triggers
- [x] Monitor supply consumption and adjust replenishment schedules accordingly
- [x] Record inventory changes after each service cycle

### C. Condition Reports
- [ ] Document property conditions before and after cleaning operations
- [x] Track repair statuses and outstanding maintenance needs
- [x] Maintain a digital archive of condition reports and inspection outcomes

## VII. Financial Operations

### A. Payment Collection
- [x] Process multiple payment methods (credit card, ACH, mobile payments) specifically for cleaning services, ensuring secure and compliant transactions
- [x] Compute cleaning staff payments based on detailed metrics (square footage cleaned, special services performed, time spent)
- [ ] Handle payment adjustments for incomplete cleaning tasks or quality issues with clear documentation
- [x] Generate cost reports broken down by cleaning type, building zone, and service frequency

### B. Vendor Payments
- [x] Generate detailed financial reports for cleaning and maintenance expenses by property, service type, and vendor—including breakdowns of labor, cleaning supply, and replacement item costs
- [x] Process vendor payments through preferred methods (ACH, paper checks) with automated scheduling
- [ ] Apply and track payment adjustments based on documented quality issues or incomplete cleaning tasks
- [x] Maintain detailed financial records for cleaning supply costs, equipment maintenance, and labor expenses

## VIII. Third-Party Integrations

### A. Property Management Systems
- [x] Provide secure API endpoints to allow data to be pushed to third party systems as needed.- [x] Support webhooks that notify property managers in real time of schedule changes, cleaning task completions, and maintenance alerts

### B. Accounting Systems
- [x] Integrate cleaning and maintenance financial records with accounting software to ensure up-to-date reconciliation of labor, supply, and equipment costs
- [ ] Continuously monitor and log all financial data synchronization operations between cleaning systems and accounting platforms, with automated alerts for discrepancies
- [x] Generate detailed year-end financial reports categorized by cleaning service types, maintenance activities, and vendor performance