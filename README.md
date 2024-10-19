# EHR-Grant-Proposal: An Investigation of the Influence of Genetic Predisposition on the Development of Cardiometabolic Conditions.
Introduction
In the rapidly evolving field of healthcare analytics, our research team set out to investigate new
identifiable risk factors for coronary heart disease (CHD). As CHD is the leading cause of death
in the United States and worldwide, targeting measures that prevent its development is of critical
clinical value [1]. It is well known that there are a variety of cardiometabolic risk factors, such as
high body mass index (BMI), that are risk factors for the development of CHD [2]. What is not
well known, however, is if there are identifiable genetic risk factors for the development of these
diagnoses. In other words, what role does genetic predisposition play in the development of
cardiometabolic conditions, therefore putting the patient at risk of the development of CHD? Or
does CHD itself have a genetic risk factor?
Our theory is that if genetic factors do play a role, an area of focus could be early detection and
intervention in the population with genetic risk. In doing so, care could be individualized and
targeted to the patient’s specific risk factors as well as social needs. More globally, this project
will leverage advanced data analytics to contribute to the broader understanding of
cardiovascular health, ultimately aiding in the identification and treatment of a culturally and
economically impactful disease. This research aims to take a step in the direction of shedding
light on the complex interplay between genetics and health, paving the way for personalized
medicine approaches and lifestyle management.
Data Management
The proposed project utilized the Coherent Dataset, a synthetic collection of approximately
290,000 Electronic Health Records (EHRs). This dataset is designed to emulate the diversity and
complexity of real-world EHRs, encompassing a comprehensive array of patient care data. It
included patient demographics, clinical conditions, observations, medications, encounters,
procedures, care plans, payers, and payer transitions. This dataset was obtained from Synthea's
repository, ensuring compliance with all privacy and security regulations (e.g., HIPAA) given it
is synthetic data. Upon acquisition, the individual components of the Coherent Dataset were in
CSV format, segmented by different aspects of patient demographics and care. The first step
involved loading these CSV files into Python using pandas, a versatile data manipulation library.
