# Reimburse-Me

www.trustreimburse.me

# Trust Beneficiary Reimbursement Portal

A mockup web application for trust beneficiaries to submit one-time reimbursement requests that fall outside their regular monthly or bi-weekly living expense allowance.

The concept is similar to a corporate card reimbursement workflow, but adapted for trust administration. A beneficiary uploads receipts, invoices, or bills, explains why the expense is outside their normal allowance, and submits the request for fiduciary review by the assigned trust advisor.

## Project Purpose

This project is intended to demonstrate a simple reimbursement intake workflow for trust administration.

Many trust beneficiaries receive recurring support for ordinary living expenses. However, unusual or unexpected expenses may require separate review. Examples may include:

- Unplanned medical expenses
- Emergency dental or vision bills
- Necessary home repairs
- Transportation emergencies
- Education-related expenses
- Other one-time needs not already contemplated by the beneficiary’s regular allowance

The portal helps collect the information a trust advisor would need to evaluate the request, document the beneficiary’s explanation, and preserve supporting receipts or invoices.

## Core User Flow

1. **Beneficiary logs in**
   - Beneficiary selects the relevant trust or account.
   - Basic beneficiary and account information is prefilled where possible.

2. **Beneficiary enters reimbursement details**
   - Requested reimbursement amount
   - Expense category
   - Description of the expense
   - Explanation of why the expense is outside the regular allowance
   - Optional notes for the trust advisor

3. **Beneficiary uploads supporting documents**
   - Receipts
   - Invoices
   - Bills
   - Proof of payment, if applicable

4. **Beneficiary certifies and submits**
   - Beneficiary confirms the information is accurate.
   - Beneficiary confirms the expense has not already been reimbursed or paid from another source.

5. **System generates advisor packet**
   - Submission is bundled into a report or PDF.
   - Report is emailed to the assigned trust advisor.

6. **Trust advisor reviews**
   - Advisor may approve the request.
   - Advisor may deny the request.
   - Advisor may request additional information.

7. **Payment processing**
   - If approved, reimbursement is processed to the beneficiary’s bank account on file.

## Important Timing Notice

The portal should clearly notify beneficiaries before and after submission that:

> One-time reimbursement requests generally require up to **3 business days** for review and decision. If approved, funds may take an additional **1 to 2 business days** to reach the beneficiary’s bank account.

This notice is intentionally displayed both before submission and after submission to help set expectations and reduce follow-up calls or emails.

## Mockup Features

The current mockup includes:

- Beneficiary-facing reimbursement request form
- Trust/account selector
- Expense amount field
- Expense category selector
- Expense description field
- Required explanation for why the request falls outside the regular allowance
- Time-sensitive request selector
- Receipt/invoice upload mock area
- Certification notice
- Submit, save draft, and cancel buttons
- Post-submission confirmation panel
- Trust advisor email/PDF packet preview
- Advisor decision options:
  - Approve
  - Deny
  - Need more information

## Suggested Future Features

Potential future enhancements include:

- Secure beneficiary authentication
- Account-specific trust advisor assignment
- Integration with bank or trust accounting software
- Real file upload and encrypted document storage
- PDF packet generation
- Email routing to assigned trust advisor
- Advisor review dashboard
- Approval workflow and audit trail
- Beneficiary notification emails
- Request status tracking
- Internal comments visible only to trust staff
- Duplicate reimbursement detection
- Bank account verification before payment
- Role-based access controls
- Multi-level approval for larger reimbursement requests

## Trust Administration Considerations

This project is a workflow mockup only. In a production environment, the language and functionality should be reviewed for:

- Trustee discretion
- Applicable trust terms
- Bank or fiduciary policies
- Privacy and data security
- Recordkeeping requirements
- Document retention requirements
- Approval authority limits
- Beneficiary communication standards
- Any special needs, government benefits, or court-supervised trust considerations

The application should avoid implying that submission guarantees approval. The beneficiary should understand that the request is subject to fiduciary review and may be approved, denied, or returned for more information.

## Example Beneficiary Explanation

Example:

> This was an unplanned medical expense from a broken arm. It was not part of my normal monthly living expenses, and I was not financially prepared to cover it from my regular allowance.

The explanation field is important because it helps the trust advisor determine whether the request is truly outside the scope of the existing monthly or bi-weekly living expense allowance.

## Technology

Current mockup:

- Static HTML
- CSS
- Basic JavaScript for mock submission behavior

No backend, database, authentication, or live document upload functionality is included at this stage.

## Local Use

To view the mockup locally:

1. Download or clone the repository.
2. Open the HTML file in a web browser.
3. Fill out the mock reimbursement form.
4. Click **Submit for Review** to display the confirmation panel.

## Repository Status

This repository currently represents an early concept/mockup. It is not production-ready and should not be used to collect real beneficiary information, trust account data, receipts, invoices, medical bills, or other sensitive documents.

## Disclaimer

This project is for demonstration and planning purposes only. It does not provide legal, fiduciary, banking, or tax advice. Any production implementation should be reviewed by appropriate legal, compliance, fiduciary, information security, and operations personnel before use.
