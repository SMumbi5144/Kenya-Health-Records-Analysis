# Kenya Hospital Analysis Project

## Description
This project analyzes patient health records from Kenyan hospitals to identify patterns in diagnoses, billing, insurance coverage, and payment status. The goal is to surface data-backed findings that can support better records management and revenue collection in the healthcare system.

## Tools Used
- Microsoft Excel
- Git
- GitHub

## Challenges Faced
- Handling missing values in the Insurance Provider column (~20% of records) without skewing analysis.
- Determining whether inconsistent diagnosis-to-department assignments were data entry errors or intentional groupings.
- Getting comfortable with Git Bash commands while documenting and committing the project.

## Findings
- Only 34.1% of bills are fully paid; 33.5% are partially paid and 32.4% are pending, leaving roughly KES 11.7 million outstanding.
- 20.2% of patients have no insurance provider recorded.
- Insurance status alone doesn't explain payment completion, even insured patients show high pending/partial rates.
- Asthma, Diabetes, and Hypertension are the top three diagnoses, together making up about 47% of cases.
- Diagnosis-to-department assignments appear inconsistent and may need validation against real clinical routing rules.

## Recommendations
1. Prioritize follow-up on pending accounts, starting with the highest bill amounts.
2. Make insurance provider a mandatory field at patient registration.
3. Investigate claims processing time and self-pay reminder processes as separate drivers of payment delay.
4. Audit department coding against clinical staff input to confirm correct specialty assignment.
5. Ensure adequate staffing and supply planning for the top three diagnoses.
