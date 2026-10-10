# Home Credit LAP Voice Agent

## Project Overview
An AI voice agent built using Retell AI to conduct preliminary customer qualification for Home Credit's Loan Against Property (LAP) offering.

## Objective
The agent contacts existing customers, explains the LAP offer, collects eligibility information, identifies disqualifying conditions, and directs eligible customers to a senior loan expert for further assistance.

## Eligibility Checks
The agent collects and evaluates:

1. Property type: Residential, Commercial, or Industrial are eligible property categories; Agricultural property is disqualified.
2. Ownership: Sole or Joint ownership.
3. Original property documents: Must be available.
4. Loan amount: Up to ₹75 lakh.
5. Occupation and income mode: Salaried or self-employed customers with bank-based income are considered; cash income is disqualified.
6. Property market value: Recorded for assessment.
7. Loan tenure: Between 3 and 15 years, inclusive.

## Conversation Handling
- Verifies the customer's identity before proceeding.
- Handles busy customers and callback requests.
- Clarifies incomplete or ambiguous answers.
- Stops the qualification process when a disqualifying condition is identified.
- Routes existing LAP customers or customers seeking EMI reduction to a specialist.
- Explains that final approval and rates require further review by a senior expert.

## Technology
- Retell AI
- AI voice conversation and prompt configuration
- Post-call custom analysis and data extraction

## Testing
The agent was tested with eligible and disqualifying customer scenarios. Audio recordings, transcripts, and call logs were saved separately for review.

## Important Note
This is a preliminary qualification assistant. It does not guarantee loan approval or final interest rates.
