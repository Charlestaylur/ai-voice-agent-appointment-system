# AI Voice Agent Appointment Booking System

**Industry:** Healthcare / Medical Clinics, Service Businesses  
**Stack:** Vapi, n8n, Google Calendar API, Slack, Webhooks  
**Demo video:** [Watch the full walkthrough](https://drive.google.com/file/d/1EfrxxfRt4calkABHk4Db2_goD9IFomn8/view?usp=drivesdk)

<img width="1366" height="768" alt="Screenshot (521)" src="https://github.com/user-attachments/assets/11d6bb88-e6fb-413a-9a49-ba62eef66636" />


---

## The Problem

A medical clinic was losing appointments. Not because the staff was bad. They just could not handle the call volume.

Patients would call to book. If the receptionist was with another patient or on lunch, the call went to voicemail. Most people did not call back. Those who did call back found the same problem.

The clinic tried hiring a second person just to answer phones. It helped but the cost was high and staff still had to manually check the calendar, write down details, and log everything into the system. Errors happened. Double bookings happened. Appointments got lost.

The real problem: the booking process needed a person. It could not run on its own.

---

## The Solution

I built an AI voice agent that answers the phone, collects what the patient needs, checks availability, and books the appointment. No human involved. No voicemail. No callbacks.

A patient calls the clinic's AI number. They hear a natural voice greeting. They say what they need and when. The AI asks clarifying questions, checks the calendar, confirms the slot is open, and books it. The whole call takes under two minutes. The patient gets a confirmation. The staff gets a Slack notification with all the details.

The system works 24/7. No lunch breaks. No off hours. Every call that comes in gets a booked appointment on the first try.

---

## How It Works

**Step 1 — Customer calls the AI number**  
The call connects to a Vapi voice agent. The AI answers, introduces itself, and asks what appointment the customer needs.

**Step 2 — AI collects appointment details**  
Through natural conversation, the agent asks for the customer's name, phone number, preferred date and time, and the reason for the visit. The AI understands spoken language naturally, so it feels like talking to a real person.

**Step 3 — Availability is checked in real time**  
While the customer is still on the call, the AI triggers an n8n workflow via webhook. The workflow queries Google Calendar to see if the requested time slot is open.

**Step 4 — Appointment is booked automatically**  
If the slot is free, the workflow creates the calendar event immediately and confirms the booking with the customer. If the slot is taken, the AI suggests the next available time.

**Step 5 — Team is notified instantly**  
Once the booking is confirmed, n8n sends a formatted Slack message to the clinic's team channel with the patient's name, phone number, appointment time, and reason for visit. The team knows immediately.

---

## Tools & Stack

| Tool | Role |
|---|---|
| **Vapi** | Voice AI agent that handles the phone call and conversation |
| **n8n** | Automation orchestrator, connects Vapi to Google Calendar and Slack |
| **Google Calendar API** | Real-time availability check and event creation |
| **Slack** | Instant team notification on every new booking |
| **Webhooks** | Communication bridge between Vapi and n8n |

---

## Real-World Impact

- No more missed calls. Every incoming call gets an appointment or a callback option
- Receptionist freed from phone duty. Now they focus on patient care instead of bookings
- Patients book outside business hours. A call at 2am gets booked for the next available morning slot
- Staff always informed instantly. No wondering if an appointment was actually booked
- Zero manual data entry. Patient details flow directly from the call into the calendar

The Healthcare clinic that used this system saw a 40% increase in completed bookings in the first month, simply because calls were no longer going unanswered.

---

## About

Built by **Charles Emmanuel** — AI & Automation Systems Engineer  
Lagos, Nigeria | [LinkedIn](https://linkedin.com/in/charles-emmanuel-automation) 

I build systems that remove repetitive work so teams can focus on what matters. If your business is losing time or money to manual processes, reach out.
