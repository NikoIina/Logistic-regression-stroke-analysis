According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

Attribute Information

- id: unique identifier
- gender: "Male", "Female" or "Other"
- age: age of the patient
- hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- ever_married: "No" or "Yes"
- work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
- residence_type: "Rural" or "Urban"
- avg_glucose_level: average glucose level in blood
- bmi: body mass index
- smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
- stroke: 1 if the patient had a stroke or 0 if not

I will use this dataset to practice predicting outcome in case of inbalanced dataset using Weighted Logistic Regression and SMOTE. I will also use summary of the final model to draw odds ratios.


По данным Всемирной организации здравоохранения (ВОЗ), инсульт занимает второе место среди причин смерти в мире, на него приходится около 11% всех смертей. Этот датасет используется для прогнозирования вероятности инсульта у пациента на основе таких входных параметров, как пол, возраст, различные заболевания и статус курения. Каждая строка в датасете содержит соответствующую информацию о пациенте.

Параметры:

- id: уникальный идентификатор
- gender: "Мужской", "Женский" или "Другой"
- age: возраст пациента
- hypertension: 0, если у пациента нет гипертонии, 1, если у пациента гипертония
- heart_disease: 0, если у пациента нет заболеваний сердца, 1, если у пациента есть заболевание сердца
- ever_married: "Нет" или "Да"
- work_type: "детский", "государственный", "никогда не работавший", "частный" или "самозанятый"
- residence_type: "Сельская" или "Городская"
- avg_glucose_level: средний уровень глюкозы в крови
- bmi: индекс массы тела
- smoke_status: "ранее курил", "никогда не курил", "курит" или "неизвестно"*
- stroke: 1, если у пациента был инсульт или 0, если нет

Я использую этот набор данных в целях практики прогнозирования результатов на основе несбалансированного набора данных с использованием Weighted Logistic Regression и SMOTE. Также на основании сводной таблицы финальной модели я посчитаю соотношения шансов для разных групп пациентов.
