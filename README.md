
# Partykidz Production Zapier Integration & Business Process Improvement

Designed and implemented an event-driven follow-up automation pipeline using Zapier, ensuring consistent and timely customer communication across multiple reservation stages.

Each workflow is triggered by specific events and concludes with targeted MailerLite communication, ensuring continuity across all customer touchpoints.

This project lasted from February to March 2026.

## Authors

- [Marina Mijatović](https://www.linkedin.com/in/marinaki/) (Operations Manager)
- [Petar Škrbić](https://www.linkedin.com/in/petar-skrbic/) (Business System Analyst)


## Other relevant links:

- [Partykidz Production Website](https://partykidzproductions.ie/)


## 🧩 Workflow #1: Lead Capture → Confirmation → Deposit Initiation

Automates the flow from customer inquiry to deposit payment initiation.

Captures client data, stores it, and sends a confirmation email with a payment link.

⚙️ Steps
+ Form Submission (Google Forms)
+ Customer details and event information are submitted.
+ Trigger (Zapier)
  
+ Workflow starts on new form entry.
+ Store Data (Google Sheets)
+ Creates a new row as a central record of the customer.
+ Send Confirmation Email (MailerLite)
  
Customer receives:
+ Booking confirmation
+ Event details
+ Payment link
+ Booking Reference ID
  
Email Redirect to Payment Form
Customer proceeds to deposit payment.

🔁 Output
+ Lead stored in database
+ Customer notified instantly
+ Payment process initiated

💡 Value
+ Eliminates manual follow-ups
+ Ensures consistent communication
+ Speeds up conversion to payment

![1th Zap structure](https://raw.githubusercontent.com/NoToolsNoCraft/partykidz-production-zapier-integration/refs/heads/main/1th%20Zapier%20Workflow.png)
