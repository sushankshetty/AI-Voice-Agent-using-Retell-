🚨 Problem Statement

Small clinics rely heavily on manual reception handling, leading to missed calls, inconsistent booking processes, and delayed emergency prioritization.

💡 Solution

Designed and deployed an AI-powered voice receptionist using Retell that automates appointment booking, prioritizes dental emergencies, follows healthcare-safe communication protocols, and drives consultation conversions.


# 🦷 Ajila’s Dental Clinic – AI Voice Receptionist

An AI-powered voice receptionist designed for Ajila’s Dental Clinic, Karkala, Karnataka.  
Built to automate appointment booking, handle patient inquiries, and prioritize dental emergencies using structured knowledge and workflow logic.

---

## 📌 Overview

This project contains the exported AI agent configuration (JSON) from Retell, along with documentation describing the clinic’s knowledge base, workflows, and system logic.

The AI receptionist is designed to:

- 📞 Answer inbound patient calls
- 📅 Book and manage appointments
- 🚨 Prioritize emergency cases (pain, swelling, trauma)
- 💰 Provide indicative treatment pricing
- 📍 Share clinic location & timings
- 🧠 Follow structured healthcare communication rules
- 🔒 Maintain professional and ethical standards

---

## 🏥 Clinic Information

**Clinic Name:** Ajila’s Dental Clinic  
**Location:** Near Joduraste Junction, Karkala Taluk, Udupi District, Karnataka – 574104  
**Doctor:** Dr. Chinmay Ajila, BDS, MDS  

The clinic focuses on:
- Ethical & evidence-based dentistry
- Transparent pricing
- Patient-first care
- Modern sterilisation standards
- Preventive and restorative dentistry

---

## 🤖 AI Agent Capabilities

### Primary Goal
Convert inbound calls into confirmed consultation appointments.

### Secondary Goals
- Emergency visit scheduling
- Follow-up bookings
- Pricing-to-consultation conversion
- General inquiry handling

### Behavioral Rules
- Never provide medical diagnosis over phone
- Never confirm treatment plans without examination
- Always encourage in-clinic consultation
- Maintain calm, professional, reassuring tone
- Follow escalation rules for urgent cases

---

## 🛠 Tools Used by the Agent

- **check_availability_cal** → Checks calendar for available slots.
- **book_appointment_cal** → Confirms and books appointment after collecting patient details.
- **transfer_call** → Escalates complex or urgent cases to clinic staff.
- **end_call** → Ends the call only after proper confirmation and summary.

---

## 📂 Repository Structure


