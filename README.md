# Home Credit LAP Qualification Voice Agent

## Project Overview

This project is a **Retell AI voice agent** designed to conduct preliminary eligibility checks for a **Loan Against Property (LAP) offer of up to ₹75 lakh**.

The agent asks qualification questions, evaluates customer responses against predefined eligibility criteria, and guides eligible customers to the next step with a senior loan expert.

## Live Demo

**Try the Retell AI Voice Agent:** [Click Here to Interact with the Agent]([https://chatgpt.com/c/YOUR_RETELL_SHARE_LINK](https://agent.retellai.com/orb/agent_dd6ffb68a44e4deabf0dfe7e84?token=fccc94c99599e6f064256b68b15cf311))

## Key Features

- **Preliminary Eligibility Checks:** Evaluates customer responses against predefined LAP qualification criteria.
- **Loan Amount Validation:** Handles requests for loan amounts up to ₹75 lakh.
- **Disqualification Detection:** Identifies responses that meet specified disqualification criteria.
- **Interest Rate Queries:** Handles customer questions about interest rates.
- **Callback Management:** Handles customer requests for callbacks.
- **Wrong-Person Handling:** Responds appropriately when the intended customer is unavailable.
- **Family Member Handling:** Manages calls answered by a family member.
- **Customer Refusal Handling:** Handles customers who decline the offer.
- **Do-Not-Call Requests:** Handles requests to stop receiving further calls.

## Eligibility Checks

The agent follows **seven qualification checks** defined in its system prompt.

- Asks the required qualification questions.
- Evaluates customer responses against predefined criteria.
- Identifies potentially eligible and disqualified applicants.
- Guides eligible customers toward the next step with a senior loan expert.

> **Important:** The agent provides preliminary qualification guidance only. It does not make final loan approval decisions or guarantee loan disbursal.

## Testing

The agent was tested using **Retell AI's Test LLM** and a shareable voice interaction on mobile.

### Test Scenarios

- [x] Eligible applicant
- [x] Income received entirely in cash
- [x] Requested loan amount above ₹75 lakh
- [x] Family member answers the call
- [x] Customer requests a callback
- [x] Customer requests no further calls

> **Note:** Callback scheduling and do-not-call execution depend on the relevant integrations being configured.

## Project Files

| File Name | Description |
|---|---|
| `Home_Credit_Voice_Agent_Assignment_Pack.docx` | Assignment documentation |
| `Home_Credit_Voice_Agent_System_Prompt.txt` | Agent instructions and qualification logic |
| `Home_Credit_Voice_Agent_Test_Matrix.txt` | Test scenarios and expected behavior |

## Technology Stack

- **Retell AI** — Voice agent development and deployment
- **Large Language Model (LLM)** — Conversational processing and response generation
- **Prompt Engineering** — Qualification rules and conversational workflow design
- **Scenario-Based Testing** — Validation of customer interactions and expected behavior

## Project Purpose

This project demonstrates:

- **Conversational AI Design**
- **Loan Qualification Workflows**
- **Eligibility-Based Decision Logic**
- **Customer Response Handling**
- **Voice Agent Testing and Validation**

## Disclaimer

This voice agent is intended for **preliminary loan qualification and demonstration purposes only**. Actual loan eligibility, approval, interest rates, and disbursal are subject to the lender's policies and assessment.
