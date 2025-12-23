# MediBuddy-Chatbot
A conversational AI chatbot I built using Kore.ai platform to help patients book medical appointments and get healthcare information without waiting on hold or dealing with complex forms.

## What This Does

I created MediBuddy to make healthcare access easier. Patients can chat with the bot to book appointments, check their scheduled visits, reschedule if needed, or get quick answers to common questions about what to bring or when to arrive.

## Features I Built

- **Appointment Booking** - The bot walks users through booking by asking for their name, which doctor they want to see, preferred date and time. I set up entity nodes to capture each piece of information properly.

- **Check Appointment Details** - Users can ask about their upcoming appointments and the bot pulls up their information.

- **Reschedule or Cancel** - If plans change, patients can modify or cancel their bookings through the conversation.

- **FAQ System** - I integrated a knowledge graph that answers common questions like "What documents do I need?" or "When should I arrive?" without needing to talk to staff.

## How I Built It

I used **Kore.ai's conversational AI platform** to design the dialog flows. Here's what I did:

- Created entity nodes to collect patient data (PatientName, DoctorName, AppointmentDate, AppointmentTime)
- Set up validation and error handling so users get helpful prompts if they enter something wrong
- Designed the conversation flow to feel natural and guide users step by step
- Built the FAQ module using Kore.ai's knowledge graph feature
- Published it on the Web/Mobile Client channel so anyone can access it

## Testing

I created batch test scenarios covering different use cases:
- Booking new appointments
- Looking up existing appointments
- Canceling appointments
- Rescheduling 
- FAQ questions

All tests passed and the bot handles these flows smoothly.

## Technologies

- Kore.ai Platform
- Dialog Management & Entity Processing
- Knowledge Graph for FAQs
- Web/Mobile Channel Integration

## Why I Built This

Healthcare facilities often struggle with phone queues and scheduling bottlenecks. I wanted to create something that reduces that friction for both patients and staff. This bot can handle appointment management 24/7, freeing up front-desk staff to focus on in-person patient care.

## Try It Out

The bot is live here: https://platform.kore.ai/xo-webclient/5be843e55be34497bbe49907b268a47bda82735fd7244b6492916612a30d3d26st99?lang=en


**Note:** I built this on a trial account, so some advanced features like bot export weren't available, but all core functionality is working as designed.
