# TRACE: A Framework to Assist Auditors in Evaluating Regulatory Compliance

## Authors:
- Vidyaraman Sankaranarayanan (DeepDive Labs, Singapore)
- Divya Venkatraman (DeepDive Labs, Singapore)

### Contact Author: vidyaraman@deepdivelabs.tech

## Abstract:
The TRACE framework is introduced as a tool to aid auditors and compliance officers in the evaluation of regulatory compliance. The framework provides two main contributions: **Compliance Mapping**, which frames the evaluation problem as a mapping between regulatory, policy, and evidence documents; and **Regulatory Prompting**, a technique derived from Legal Syllogism Prompting, which provides an initial judgement of compliance to assist auditors. TRACE was tested on the Data Protection Trustmark (DPTM) certification requirements published by the Infocomm Media Development Authority (IMDA) in Singapore.

## Key Features:
1. **Compliance Mapping**: Mapping sections of regulatory documents to corresponding sections in policy and evidence documents using Large Language Model (LLM) techniques.
2. **Regulatory Prompting**: Applying legal syllogism to evaluate if a policy document satisfies regulatory requirements, generating a preliminary judgement of compliance (Met, Not Met, Partially Met).

## Implementation:
The framework follows a structured, three-step process:
1. **Extraction of Requirements**: Extracting key regulatory requirements from source documents.
2. **Compliance Mapping**: Identifying relevant sections from policy and evidence documents that map to the regulatory requirements.
3. **Judgement on Policy**: Using regulatory prompting to evaluate if the policy satisfies the extracted regulatory requirements, followed by a judgement (Met, Not Met, Partially Met).

## Testing and Validation:
The framework was tested using the DPTM certification requirements, and privacy policies from DBS Bank and Grab. Results demonstrated the effectiveness of TRACE in providing structured compliance evaluations, though challenges related to token limitations and reproducibility were noted.

## Conclusion:
TRACE streamlines the audit process, enhances accuracy in compliance assessments, and provides a foundation for further research in the application of LLMs in regulatory compliance.

## Repository:
Visit the full implementation and example prompts on [GitHub](https://github.com/svidyaraman/TRACE-Framework).
