# Appointment Booking Patient Management System
# Salesforce Appointment Management System

A Salesforce-based Appointment Management System designed to manage doctors, patients, time slots, and appointments.

## Project Overview

This project provides a Salesforce solution for managing appointment booking and doctor availability.

The system helps manage:

- Doctors
- Patients
- Time Slots
- Appointments
- Appointment Status
- Doctor Availability

## Technologies Used

- Salesforce
- Apex
- Lightning Web Components (LWC)
- SOQL
- Salesforce Flow
- Apex Triggers
- Custom Objects
- Salesforce Reports & Dashboards

## Key Features

### 1. Doctor Management
Manage doctor information, specialization, and availability.

### 2. Patient Management
Maintain patient information and appointment history.

### 3. Time Slot Management
Create and manage available appointment time slots.

### 4. Appointment Booking
Patients can book appointments based on available doctors and time slots.

### 5. Double-Booking Prevention
Apex Trigger logic checks existing appointments and prevents multiple appointments for the same doctor, date, and time slot.

### 6. Automation
Salesforce Flow is used to automate appointment-related business processes.

### 7. Lightning Web Components
LWC is used to provide an interactive user interface for appointment-related functionality.

## Salesforce Development Concepts

- Apex Classes
- Apex Triggers
- SOQL
- LWC
- Salesforce Flow
- Data Modeling
- Validation
- Reports & Dashboards
- Salesforce Automation

## Project Structure

force-app/
└── main/
    └── default/
        ├── classes/
        ├── triggers/
        ├── lwc/
        ├── objects/
        └── flows/

