<div align="center">

# EcoCycle CTG

**E-Waste Collection and Recycling Platform for Chattogram City Corporation**

Presented by the Sociology Club, Premier University Chittagong — World Environment Day

</div>

---

## Overview

EcoCycle CTG is an AI-powered Android application developed to address the growing problem of electronic waste in Chattogram. The project was initiated by the Sociology Club of Premier University Chittagong on the occasion of World Environment Day, with the goal of creating practical, citizen-facing tools that promote responsible disposal and recycling of electronic waste within Chattogram City Corporation areas.

Electronic waste, or e-waste, is one of the fastest-growing waste streams in the world. Devices such as mobile phones, laptops, batteries, and household appliances contain hazardous materials including lead, mercury, and cadmium, which cause serious damage to soil, water, and human health when discarded improperly. EcoCycle CTG bridges the gap between citizens who want to dispose of their e-waste responsibly and the collection infrastructure that exists to handle it — making the process easy, accessible, and guided by AI.

---

## Event Presentation

<div align="center">

<img width="860" alt="World Environment Day Presentation Slide 1" src="https://github.com/user-attachments/assets/ac04a4cf-be95-4783-95c9-6e6da3d5bfa9" />

<br><br>

<img width="860" alt="World Environment Day Presentation Slide 2" src="https://github.com/user-attachments/assets/59502775-1f02-49f0-a442-af59bb8decb8" />

</div>

---

## App Screenshots

<div align="center">

<img width="160" alt="Home Screen" src="https://github.com/user-attachments/assets/3346f4ab-d339-4e85-94ee-48d98d369fd3" />
<img width="160" alt="Schedule Pickup" src="https://github.com/user-attachments/assets/32e8193f-aba6-4a04-b917-8c9fa998da18" />
<img width="160" alt="AI Assistant" src="https://github.com/user-attachments/assets/02840984-3c91-4a4a-a1ca-c77834702566" />
<img width="160" alt="Drop-off Map" src="https://github.com/user-attachments/assets/0c03b19e-14ea-4730-abbc-0cfa8b0bb3b7" />
<img width="160" alt="Learn and Educate" src="https://github.com/user-attachments/assets/bc025c03-da2a-4c42-906c-3a2b4aa7a461" />

<br><br>

<img width="160" alt="Recycling Guide" src="https://github.com/user-attachments/assets/b4ddaa26-74ed-4edc-b174-63400a9200aa" />
<img width="160" alt="Item Scanner" src="https://github.com/user-attachments/assets/040a4159-38ad-4964-b2a7-9badebd5a815" />
<img width="160" alt="Pickup History" src="https://github.com/user-attachments/assets/784dc670-c1e9-4808-a512-b7935db4c145" />
<img width="160" alt="User Profile" src="https://github.com/user-attachments/assets/dfa9a42c-1a67-402e-9ae8-0028f385692f" />

</div>

---

## IoT Integration — Smart Dustbin System

EcoCycle CTG goes beyond a mobile app. The project includes a physical IoT-based Smart Dustbin system that works alongside the app to create a complete e-waste management solution for Chattogram City.

### IoT System Architecture

The IoT system connects physical smart dustbins to the EcoCycle CTG platform in real time. Sensors embedded in the dustbin monitor fill levels, detect the type of waste deposited, and transmit data to the cloud. This allows the app and city authorities to track bin status, dispatch collection when needed, and maintain an accurate picture of e-waste volume across the city.

<div align="center">

<img width="860" alt="EcoCycle CTG IoT System Architecture" src="https://github.com/user-attachments/assets/47426f85-f4a7-4b67-b3a0-911bab064b41" />

</div>

### Smart Dustbin

The Smart Dustbin is a purpose-built physical unit designed for e-waste collection in public spaces, university campuses, and residential areas. It uses IoT sensors to detect when an item is deposited, identify whether it qualifies as electronic waste, and automatically update the EcoCycle CTG system. When the bin reaches capacity, a notification is triggered for collection by the city's recycling team.

<div align="center">

<img width="860" alt="EcoCycle CTG Smart Dustbin" src="https://github.com/user-attachments/assets/0310fc95-fb60-4daf-87a3-39d5a417400d" />

</div>

---

## Features

### Schedule E-Waste Pickup

Citizens can request a doorstep collection for their electronic waste by selecting a date, time slot, and waste category. The system confirms and tracks the pickup in real time.

### Drop-off Location Finder

An interactive map displays nearby authorized e-waste drop-off centers within Chattogram City Corporation. Users can get directions directly from the app.

### AI-Powered Assistant

Powered by Google Gemini, the AI assistant answers questions about what qualifies as e-waste, how to prepare items for recycling, and what the environmental impact of proper disposal is.

### Item Scanner

Users can scan or photograph a device or item. The app identifies whether it qualifies as e-waste and provides specific guidance on the correct disposal method for that item type.

### Education and Awareness

A dedicated learning section covers topics such as hazardous materials in electronics, the recycling process, local environmental laws, and how responsible disposal contributes to public health.

### Pickup History and Tracking

Users can view a full log of their past pickup requests including dates, item types, and collection status — keeping a personal record of their contribution to the environment.

---

## How It Works

```
User opens app
      |
      v
Scans item or enters waste details
      |
      v
Chooses pickup scheduling or finds nearest drop-off point
      |
      v
AI assistant provides guidance and confirms next steps
      |
      v
E-waste deposited in Smart Dustbin or collected at doorstep
      |
      v
IoT system updates bin status and notifies collection team
      |
      v
E-waste is collected and recycled responsibly
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Kotlin |
| UI Framework | Jetpack Compose |
| AI Backend | Google Gemini API |
| Build System | Gradle (Kotlin DSL) |
| IDE | Android Studio |
| IoT Hardware | Smart Dustbin with embedded sensors |
| IoT Connectivity | Cloud-connected real-time monitoring |

---

## Getting Started

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (latest stable)
- JDK 11 or higher
- A valid [Gemini API Key](https://aistudio.google.com/app/apikey)
- Android device or emulator (API 24+)

### Setup

1. Clone the repository

```bash
git clone https://github.com/rahul-3613/EcoCycle-CTG-_-app.git
cd EcoCycle-CTG-_-app
```

2. Create a `.env` file in the project root and add your API key

```env
GEMINI_API_KEY=your_actual_api_key_here
```

3. Open the project in Android Studio and allow Gradle to sync

4. Remove the following line from `app/build.gradle.kts`

```kotlin
signingConfig = signingConfigs.getByName("debugConfig")
```

5. Run the app on an emulator or physical device

---

## Project Details

| | |
|---|---|
| Presented by | Sociology Club, Premier University Chittagong |
| Occasion | World Environment Day |
| Competition Result | Champions out of 21 teams |
| Target Area | Chattogram City Corporation |
| Platform | Android + IoT |
| AI Backend | Google Gemini API |
| Primary Goal | Reduce e-waste environmental impact in Chattogram |

---

## App Demo

[Watch Demo on Google Drive](https://drive.google.com/file/d/1I9MKUGeo9RCmD4KIQMGJLpRIlTI52HvP/view?usp=drive_link)

---

## Security

Never commit your `.env` file or `debug.keystore` to version control. Both are listed in `.gitignore` by default. API keys are injected at runtime via the Secrets Gradle Plugin.

---

## License

Distributed under the Apache License 2.0.
