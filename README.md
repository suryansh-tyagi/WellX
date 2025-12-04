# WellX – Health Guidance Mobile App

WellX is an Android mobile application that helps users to interpret symptoms and receive quick guidance, including home remedies, diet advice, and warnings when medical attention might be needed. The app is designed to be simple, clear, and accessible to all.

## Description

WellX offers:
- Symptom understanding in plain language  
- Provides simple home remedies based on the user’s symptoms.  
- Recommended diets and nutrition advice based on symptoms (What to eat & What to avoid)
- Alerts for serious symptoms (When to see a doctor)  
- Support for multiple languages (English & Hindi)

This project was developed using Android Studio, with AI-assisted coding (ChatGPT, Gemini, and Perplexity) for debugging, logic, and feature implementation. The app uses a custom JSON-based dataset and Firebase Cloud Messaging for notifications.

## Demo

Watch the working MVP:  
https://www.youtube.com/watch?si=iPAKIxuTjq638g2T&v=6sU5F-xZrPo&feature=youtu.be

## Features

- Symptom checker (simple & clean UI)  
- Remedies & diet suggestions  
- Doctor-alert warnings  
- Multi-language support (English & Hindi)  
- Clean native Android UI & fast performance  

## Technical Stack

**Platform**: Android Studio (Java/Kotlin)  
**Logic & Workflow**: Rule-based logic using custom JSON data  
**Notifications**: Firebase Cloud Messaging (For push notifications)  
**Dataset**: Custom JSON file (17 conditions, expandable)  
**Support Tools**: AI-assisted coding for debugging and iteration  

## Usage (MVP Flow)

1. User enters symptoms  (single or many)
2. App processes input and matches against known conditions  
3. Shows possible issue + remedies  (based on no. of symptoms)
4. Provides diet advice (what to eat / avoid)  
5. Gives notice if doctor consultation is recommended  

## Current Status

- Core MVP ready (symptom → remedies → diet → doctor alerts)  
- Dataset (17 conditions) built and integrated  
- Multi-language support implemented (English & Hindi)  
- UI & navigation screens completed  
- Basic safety disclaimer + risk alerts implemented  

## Future Plans

- Expand dataset (100+ conditions)  
- Add AI-based symptom analysis (by using api key - for better & accurate results)
- Enable user accounts & history tracking  
- Add voice-based symptom input + more languages  
- Include calorie/nutrition tracker  
- Optional doctor-consult connect feature  
- Add offline mode & full backend/API integration  

## Getting Started

To try/build the app:

