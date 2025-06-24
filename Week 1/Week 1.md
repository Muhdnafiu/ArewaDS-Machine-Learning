# Arewa Data Science Week 1

## Simple & Brief (for Beginners)

### 1. Helping Kids Learn Better
1. **Data to collect:**  
   - Test and homework scores  
   - Attendance and time spent on learning apps  
   - Which lessons students find hard

2. **How to collect:**  
   - From school gradebooks and apps  
   - Quick in-class polls or quizzes

3. **How to store & size:**  
   - In a secure online database (e.g. Google Sheets or a school system)  
   - About 10–50 MB per year for a small school

4. **What you learn & decide:**  
   - Spot students who need extra help early  
   - Find which lessons work best and adjust teaching

---

### 2. Managing Vaccines in a Pandemic
1. **Data to collect:**  
   - Who got which vaccine, when, and where  
   - How many doses are left at each clinic  
   - No-show (missed) appointments

2. **How to collect:**  
   - From hospital/clinic computers  
   - Scanning vials and appointment apps

3. **How to store & size:**  
   - In a protected database (e.g. a hospital system)  
   - Tens of MB to a few GB for a country’s data

4. **What you learn & decide:**  
   - Send more vaccines to busy clinics  
   - Plan mobile clinics where coverage is low  
   - Reduce wasted doses by tracking expiries

---

### 3. Staying Productive at Work
1. **Data to collect:**  
   - Time spent on tasks and apps  
   - Number of meetings and emails  
   - Self-rated focus and breaks taken

2. **How to collect:**  
   - Using simple time-tracker apps or browser plugins  
   - Quick end-of-day check-in form

3. **How to store & size:**  
   - In a small local file or cloud spreadsheet  
   - Under 100 MB per year for one person

4. **What you learn & decide:**  
   - Find your best work hours and schedule deep tasks then  
   - Spot when meetings or emails break your flow and adjust  
   - Make sure you take breaks to avoid burnout

---

## Detailed Guide

| Problem Domain | Problem                                                    | Which data to collect                                                                                                                                                                  | How to store the data                                                                                                                                                                  | Which insights/decisions we can make                                                                                                                                                                                                                                                                                                             |
|---------------|-------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Education     | Monitoring and improving student learning outcomes          | Student demographics (age, gender, socioeconomic status), course enrollments, grades and test scores, attendance and discipline logs; digital engagement logs (LMS clickstreams, time on content, quiz responses) | Collected via school information systems, LMS platforms, online assessments, and surveys. Stored in a cloud database or educational data warehouse (with data lakes for raw logs). A large district might accumulate tens of GB (or more) of data per year. | Analytics can flag at-risk students (e.g. declining scores or poor attendance) for targeted interventions; aggregate metrics let administrators allocate resources to struggling schools and adjust programs; tracking assessment outcomes helps evaluate curriculum changes and guide policy decisions. fileciteturn1file0 |
| Vaccination   | Maximizing immunization coverage and preventing outbreaks   | Immunization records (patient ID, vaccine type, dose date/location) and demographics (age, health status); disease surveillance data (cases and hospitalizations by location); vaccine supply-chain logs (inventory levels, cold-chain temperature records); surveys/social media on vaccine attitudes | Data collected via healthcare systems, immunization registries, clinics and mobile apps; IoT sensors monitor storage (e.g., vaccine fridge temperatures). Stored in secure health data warehouses or cloud health platforms (using HL7/FHIR). A national registry may hold millions of records (GB–TB scale). | Analytics can reveal under-vaccinated areas and zero-dose populations (e.g. geospatial AI helped UNICEF locate ~1.3M unreached children) for targeted outreach; real-time coverage and case data guide vaccination policy and resource allocation; predictive models can forecast outbreaks and optimize supply distribution. fileciteturn1file2 |
| Productivity  | Enhancing workforce and operational efficiency              | Work/task logs, time-tracking and output metrics; communication/collaboration data (email/chat volumes, meeting durations); employee feedback surveys. In manufacturing: machine telemetry (output rates, temperature, vibration, energy use). | Use an enterprise data warehouse or cloud data lake. Structured data (HR/ERP systems) in relational/NoSQL databases; high-frequency IoT sensor streams in time-series or big-data stores. Data volumes vary: e.g., an industrial IoT installation might log tens of millions of data points (GBs), while a mid-size company’s activity logs could be tens of GB per year. | Analytics pinpoints bottlenecks and best practices (models identify which tasks or conditions yield higher productivity); predictive maintenance on sensor data reduces downtime (as when analytics on 40M+ readings boosted a furnace’s output); managers then adjust schedules, training, and workflows to boost efficiency. fileciteturn1file3 |
