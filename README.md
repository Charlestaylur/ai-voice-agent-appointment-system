# AI Voice Agent Appointment Booking System

> AI-powered voice agent that handles inbound patient calls, collects details, books medical appointments, and notifies the clinic team automatically using Vapi, n8n, Slack, and Gmail.

**Industry:** Healthcare / Medical Services
**Built for:** Medical clinics that want to handle appointment booking over the phone automatically without routing every call through a receptionist.

---

## Demo

[Watch the full walkthrough →](https://drive.google.com/file/d/1EfrxxfRt4calkABHk4Db2_goD9IFomn8/view?usp=drivesdk)

<img width="846" height="402" alt="Github recept" src="https://github.com/user-attachments/assets/cb12ac47-576a-40bb-a070-c03571cd9513" />


---

## The Problem

Medical clinics receive a high volume of appointment calls every day. Receptionists have to answer every call, collect patient details, check availability, confirm the booking, and follow up with a confirmation. When the front desk is busy, calls go unanswered. Patients get frustrated. Appointments get missed or double-booked.

The process is repetitive, time-consuming, and does not need a human for the majority of cases.

---

## The Solution

An AI voice agent now handles inbound appointment calls for the clinic. It picks up the call, speaks naturally with the patient, collects their details, and books the appointment. Once the booking is confirmed, the clinic team gets an instant Slack notification and the patient receives a confirmation email via Gmail. The front desk is freed up entirely for in-person care.

---

## How It Works

1. **Patient calls the clinic** — The call is received by the Vapi voice agent, which picks up immediately and greets the patient by name once identified.
2. **Agent collects patient details** — The AI agent conducts a natural voice conversation to gather the patient's name, contact information, preferred date and time, and reason for the visit.
3. **Appointment is booked** — The agent confirms the appointment details with the patient and triggers the n8n workflow to process and record the booking.
4. **Clinic team is notified on Slack** — An instant Slack notification goes to the relevant team channel with a summary of the new booking so the team is aware immediately.
5. **Patient receives a confirmation email** — Gmail sends a formatted confirmation email to the patient with their appointment details, clinic information, and any preparation instructions.

---

## Tech Stack

| Tool | Role |
|---|---|
| **Vapi** | Hosts and runs the AI voice agent that handles inbound patient calls |
| **n8n** | Workflow orchestration layer that processes booking data and triggers notifications |
| **OpenAI API** | Powers the agent's natural language understanding and conversational responses |
| **Slack** | Real-time booking notifications to the clinic team |
| **Gmail** | Automated appointment confirmation emails to patients |
| **Webhooks** | Connects Vapi to n8n, passing booking data when a call completes |

---

## Results

- Inbound appointment calls are handled automatically without receptionist involvement
- Patients get immediate responses at any time, including outside clinic hours
- Clinic team receives instant Slack alerts for every new booking
- Patients receive a professional confirmation email seconds after the call ends
- Front desk staff freed up to focus entirely on in-person patient care

---

## About

Built by **Charles Emmanuel** — AI & Automation Systems Engineer.  
Lagos, Nigeria | [LinkedIn](https://linkedin.com/in/charles-emmanuel-automation) | charlestaylurr@gmail.com

I build systems that remove repetitive manual work so teams can focus on what actually matters. If your business is losing time or money to broken processes, reach out.
