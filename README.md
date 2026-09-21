# DroBud
Medication delivery by drone, for Medirite and Shoprite Sixty60.**

DroBud is a prototype web application that allows caregivers to request chronic medication delivery for elderly or homebound patients. The system supports two delivery methods:

1. **Drone Delivery** — Medication is dispatched to the patient's address via drone.
2. **Mall Hub Collection** — Medication is reserved for collection at a Medirite hub inside a selected mall.

---

## The Problem

Elderly South Africans, especially in outlying areas, struggle to collect chronic medication. Long queues, no transport, and physical pain make a simple pharmacy visit impossible. Caregivers exist, but the journey is still a barrier.

## The Solution

DroBud is a software layer that integrates with existing pharmacy platforms like Medirite. It handles the caregiver order flow, prescription upload, delivery tracking, and POPIA-compliant data collection.

## Tech Stack (Week 1 Prototype)

| Layer | Technology |
| :--- | :--- |
| Frontend | HTML5 |
| Map | Leaflet.js + OpenStreetMap |
| Styling | Inline CSS (to be extracted later) |
| Backend | *Coming in Week 2 (Python/Flask)* |
| Database | *Coming in Week 2 (Supabase)* |

##  Week 1 Features

- [x] Landing page with DroBud branding
- [x] Order form (patient details, medication, prescription upload)
- [x] Delivery method selection (drone or mall hub)
- [x] Mall hub dropdown (Cresta, Northgate, Brightwater, Randridge, Ferndale)
- [x] POPIA consent checkbox
- [x] Privacy policy section
- [x] FAQ accordion
- [x] WhatsApp contact link
- [x] Simulated drone tracking map with ETA and distance

##  How the Map Works

The map uses **Leaflet** with OpenStreetMap tiles. A drone marker is animated from a Medirite hub to a client destination. The ETA and distance update in real time. This is a **simulation** — real drone telemetry would require CAA-approved BVLOS operations.

## 🚀 How to Run

