# Payment-Ready Template

Use this template when a buyer is ready to pay for Agent Ops Command Center but needs a checkout method, invoice, purchase order, reimbursement record, or payment-proof workflow first.

## Payment Readiness Summary

| Field | Value |
| --- | --- |
| Product | Agent Ops Command Center |
| Package | Team license - 7 seats |
| Gross amount | `$203` |
| Individual seat reference | `$29` |
| Buyer / team |  |
| Payment owner |  |
| Delivery owner |  |
| Preferred checkout method |  |
| Required payment proof | Checkout, receipt, payout, or seller-dashboard evidence |
| Target decision date |  |

## Buyer Intent

| Detail | Note |
| --- | --- |
| Ready to pay? |  |
| Checkout method needed | Card / invoice / purchase order / reimbursement / other |
| Procurement blocker |  |
| Billing blocker |  |
| Security or vendor review blocker |  |
| Receipt or tax requirement |  |
| Delivery acceptance owner |  |

## Payment-Ready Request

```text
Payment-ready request: Agent Ops Command Center
Request package: Team license - 7 seats - $203 gross.
Buyer is ready to pay when the preferred checkout method is available.
Preferred checkout:
Required proof: checkout, receipt, payout, or seller-dashboard evidence.
Delivery rule: private paid ZIP delivered only after payment proof exists.
Primary team request URL: https://ivelly42.github.io/agent-ops-command-center/team-request-url.html
Checkout status: https://ivelly42.github.io/agent-ops-command-center/checkout-status.json
```

## Payment Proof Checklist

- [ ] Checkout page or invoice exists
- [ ] Buyer payment can be completed through the preferred method
- [ ] Receipt, payout, or seller-dashboard evidence can be captured
- [ ] Paid ZIP delivery manifest exists
- [ ] Archive digest can be verified
- [ ] Buyer acknowledgement or acceptance record exists

## Decision Record

- [ ] Ready to pay when checkout is ready
- [ ] Need invoice before payment
- [ ] Need purchase order before payment
- [ ] Need reimbursement approval first
- [ ] Need vendor or security review first
- [ ] Evaluating preview only

## Revenue Rule

Payment-ready notes, order intent, page views, stars, forks, template use, and downloads are not revenue.

Count revenue only after checkout, receipt, payout, or seller-dashboard evidence proves payment.
