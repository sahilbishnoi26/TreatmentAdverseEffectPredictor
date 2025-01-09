# Predicting patients likely to experience ADE from cancer treatment using machine learning 

- Tackled the issue of a cancer treatment drug causing 25% of patients to discontinue therapy due to severe side effects. Analyzed six months of medical and insurance claims data prior to treatment, which included diagnosis codes and drug codes. Flagged entries where diagnosis codes or drug codes matched a predefined list of adverse effects associated with the treatment.

- Trained an ensemble of classification machine learning models on cleaned and transformed data with these flagged entries, along with features such as age, gender, race, prescription costs, and total accumulated costs. The best model achieved 85% accuracy on test data while ensuring fairness across gender and race.

- Identifying high-risk patients allowed the firm to develop targeted intervention strategies to proactively manage these patients both physically and mentally, reducing dropout rates. Recommendations included personalized follow-ups, patient education, medication management, integrated care teams, and leveraging technologies such as mobile health apps and telemedicine to improve treatment adherence and outcomes.
