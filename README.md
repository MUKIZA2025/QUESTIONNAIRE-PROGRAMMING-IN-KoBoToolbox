# QUESTIONNAIRE-PROGRAMMING-IN-KoBoToolbox

## Project Overview

This project was designed as a **learning exercise in programming digital questionnaires** using KoBoToolbox. The scenario is **the adoption of electric vehicles (EVs) in Kigali City**, including motorcycles, public buses, and private cars.  

While the scenario simulates a real-world research context, the main purpose of this project was **educational**: to learn how to design and program a survey with multiple sections, skip logic, numeric validation, GPS capture, and bilingual setup.  

Students gained practical skills in creating surveys that are ready for real-world deployment while practicing programming logic, constraints, and multilingual labeling.

---
## Access the Survey

You can view and test the Kigali Electric Vehicle (EV) Survey on KoBoToolbox using the following link:

[View the Kigali EV Survey](https://ee.kobotoolbox.org/x/4WGbVtqa)

> Note: This survey includes both English and Kinyarwanda versions. It is designed for **learning and demonstration purposes**. Responses will not be collected unless the survey is deployed in a real project environment.


## Questionnaire Sections

The survey includes six main sections:

1. **Consent and Introduction** – displayed to all respondents. It provides a short explanation of the survey purpose, emphasizes confidentiality, and includes a consent question asking if respondents agree to participate. This section introduces ethical programming concepts.

2. **Vehicle Owners** – displayed only to respondents who are motorcycle riders, bus operators, or private car owners. This section collects information on age, years of experience, daily fuel costs, perception of EV infrastructure readiness, and barriers to EV adoption. Students learned to program skip logic, numeric validations (age between 18–80, experience and costs ≥ 0), 1–5 Likert scale questions, and conditional text boxes for “Other” responses.

3. **Passengers** – displayed only to respondents categorized as passengers. This section collects information on daily transport usage, daily costs, perception of EV cost-effectiveness, and ease of payment on a scale of 1 to 5. Skip logic ensures only relevant respondents see these questions.

4. **Transport Officials** – displayed only to respondents who are transport officials. This section includes questions on knowledge of EV policies, infrastructure readiness (1–5 scale), adoption barriers, incentives, opinion on phasing out fuel vehicles, additional comments, and optional GPS capture. Students learned how to program relevance formulas, scale validations, and GPS configuration.

5. **Perception and Policy Views** – displayed to all respondents. This section collects opinions on EV adoption, environmental impact, and preferred policies. It includes Likert scale questions, multiple-choice questions with “Other” options, and open-ended text questions for additional recommendations.

6. **Transport Official Section (Detailed)** – a continuation of the transport official section, designed to reinforce skip logic, numeric validation, GPS capture, and bilingual labels. It allows students to practice advanced conditional logic and relevance programming in KoBoToolbox.

---

## Skip Logic and Relevance

- Sections are displayed only for relevant respondent categories: Vehicle Owners (motorcycle, bus, private car), Passengers, Transport Officials.
- “Other” text boxes appear only when “Other” is selected in multiple-choice questions.
- GPS capture is displayed only for transport officials.
- Students learned to implement complex conditional logic to control the flow of the survey.

---

## Validation Criteria

- Age: between 18 and 80 years.
- Years of experience and daily fuel cost: zero or positive numbers.
- Likert scale questions: 1–5.
- GPS accuracy: less than 10 meters.
- Constraint messages provided in **English** and **Kinyarwanda** to guide respondents.
- Students learned how to program validation constraints and error messages in KoBo.

---

## Bilingual Implementation

- English labels are default.
- Kinyarwanda labels are added using KoBo multi-language editor.
- Choice names remain consistent to maintain skip logic.
- Constraint messages are translated to ensure clarity and usability for Kinyarwanda-speaking respondents.

---

## GPS Capture

- Type: `geopoint`.
- Accuracy threshold: less than 10 meters.
- Relevant only for transport officials.
- Students learned to program GPS questions with relevance and accuracy constraints.

---

## Deployment

- Platform: KoBoToolbox.
- Offline collection: KoBoCollect (Android).
- Online collection: Enketo (Web browser).
- Skip logic, validations, and bilingual labels function in both offline and online modes.
- Respondents can toggle between English and Kinyarwanda at the start of the survey.

---

## Learning Outcomes

Through this project, students learned to:

- Design complex surveys with multiple sections.
- Implement **skip logic and relevance formulas**.
- Program **numeric validations and scale constraints**.
- Add **conditional “Other” text boxes**.
- Capture **GPS data with accuracy constraints**.
- Implement **bilingual labels and messages**.
- Test and deploy a survey in KoBoToolbox, ready for real-world data collection.

This project serves as a **practical learning tool** for students to understand survey programming, data validation, and logic implementation while using a realistic scenario of Kigali’s potential transition to electric vehicles.
