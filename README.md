# FeatureImportance

The given code explores local and global important features from given dataset using LIME Python package. For the purpose, XGB Classifier is implemented and then is used for feature selection purpose.

The given dataset is of Portuguese banking institution which is about their marketing campaigns (phone calls). The dataset provides the bank customers information that includes 41,188 records with 21 fields. The target variable (y) in given dataset which is to be predicted refers to term deposit, and gives a value of 0 and 1 which shows whether term deposit will be subscribed by client or not?

# Input variables

age (numeric)

job : type of job (categorical: “admin”, “blue-collar”, “entrepreneur”, “housemaid”, “management”, “retired”, “self-employed”, “services”, “student”, “technician”, “unemployed”, “unknown”)

marital : marital status (categorical: “divorced”, “married”, “single”, “unknown”)

education (categorical: “basic.4y”, “basic.6y”, “basic.9y”, “high.school”, “illiterate”, “professional.course”, “university.degree”, “unknown”)

default: has credit in default? (categorical: “no”, “yes”, “unknown”)

housing: has housing loan? (categorical: “no”, “yes”, “unknown”)

loan: has personal loan? (categorical: “no”, “yes”, “unknown”)

contact: contact communication type (categorical: “cellular”, “telephone”)

month: last contact month of year (categorical: “jan”, “feb”, “mar”, …, “nov”, “dec”)

day_of_week: last contact day of the week (categorical: “mon”, “tue”, “wed”, “thu”, “fri”)

duration: last contact duration, in seconds (numeric).

campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

previous: number of contacts performed before this campaign and for this client (numeric)

poutcome: outcome of the previous marketing campaign (categorical: “failure”, “nonexistent”, “success”)

emp.var.rate: employment variation rate — (numeric)

cons.price.idx: consumer price index — (numeric)

cons.conf.idx: consumer confidence index — (numeric)

euribor3m: euribor 3 month rate — (numeric)

nr.employed: number of employees — (numeric)
