# Compliance (Ukraine)

Not legal advice: have your counsel review your flows. The rules most senders on AllyMailer meet:

| Law | Key requirements |
|---|---|
| **Law of Ukraine "On Personal Data Protection"** (No. 2297-VI) | Consent or another legal basis for processing the address; informing the person of the purpose and their rights; answering access and deletion requests. |
| **Law of Ukraine "On Electronic Commerce"** (No. 675-VIII, Art. 11) | Commercial electronic messages only with the recipient's **consent**; the sender identified; an easy way to refuse further messages in every message. |
| **Law of Ukraine "On Advertising"** | Advertising must be identifiable as such and must not mislead. |
| GDPR | When you also mail people in the EU — most Ukrainian senders do. |

## Practice

- **Double opt-in** with a stored record: address, time, form, consent text, IP.
- A separate, unticked consent checkbox for marketing.
- Every marketing email: the sender's name and contacts, a one-click unsubscribe; honour unsubscribes at once
  (`unsubscribed` webhook events, `suppression/list`).
- Transactional email (orders, password resets, notifications) without promotional blocks.
