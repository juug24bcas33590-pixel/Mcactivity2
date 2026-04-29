 EcoNest Smart Home Energy Optimizer
Aim & Algorithm
Aim

To design and develop an Android-based smart home application named EcoNest using MIT App Inventor that helps users monitor, analyze, and optimize their home energy usage.

The application aims to:

 Integrate weather and energy data to provide smart insights
 Allow users to connect and manage home devices (thermostat, solar, battery, etc.)
 Generate an Eco Score based on energy efficiency
 Provide AI-based automation suggestions for saving energy
 Display energy consumption, savings, and carbon footprint statistics
Deliver a simple, user-friendly interface for smarter and greener living

Algorithm
Step 1: Start
 Launch the EcoNest application.
Step 2: Initialize Variables

 Initialize global variables:

  * User name
  * Connected devices list
  * Eco score
  * Energy savings (daily, weekly, monthly)
  * CO₂ reduction data
  * Notifications list
Step 3: Display Splash Screen
 Show app logo and introduction.
 Provide Get Started and Login options.
Step 4: Device Setup

Display list of smart devices:

  * Thermostat
  * Blinds
  * Solar panels
  * Battery
  * EV charger
  * Lights
* User selects (checks) connected devices.
* Count and display number of connected devices.
* Store device data using TinyDB.
Step 5: Navigate to Dashboard

* Open main dashboard screen.
* Display greeting message and location.
Step 6: Load Data
* Load:
  * Weather data (API or dummy data)
  * Energy usage data
  * Solar generation data
* Update UI labels accordingly.
* Step 7: Calculate Eco Score
* Compute eco score based on:
  * Energy consumption
  * Renewable usage (solar)
  * Device efficiency
* Display score and ranking.
Step 8: Display Energy Status
* Show:
  * Solar generation
  * Battery level
  * Home energy usage
  * Grid status (buy/sell)
Step 9: Generate AI Automation Schedule
* Apply rule-based logic:
  * If high temperature → suggest pre-cooling
  * If solar peak → schedule heavy usage
  * If battery high → optimize usage
* Display automation cards with savings estimate.
Step 10: User Approval
 If user clicks Approve Automations:

   Save action
   Add notification
   Update system state

Step 11: Display Statistics
Show:

   Daily, weekly, monthly savings
   CO₂ reduction
   Eco score summary
 Display 7-day energy forecast using ListView.

Step 12: Notifications
Store alerts such as:

 Savings achieved
 AI recommendations
Display in notification screen.
Step 13: Navigation Control
 Allow switching between:

 Dashboard
 Stats
  Devices
  Settings

Step 14: Data Persistence
Store key values using TinyDB:
  Devices connected
  Eco score
  Notifications
  
Step 15: End
 Continue app operation until user exits.



https://github.com/user-attachments/assets/14ddca66-0ac5-4c73-b1f0-8d244da5879d


