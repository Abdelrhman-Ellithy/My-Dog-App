# 🐶 Manual Testing for My Dog App

Welcome to the **My Dog Application** repository! 🐾 This mobile app connects to a device hanging around your dog's neck, allowing you to call your dog, track its location via GPS, and manage important information about your furry friend.

## 📱 Features

- **User Registration**: Users can register with their email, password, and phone number, providing their dog's info (Name, Age, Type) for a personalized experience. 📝
- **Dog Calling**: Call your dog using voice commands while connected via Bluetooth (within 10m range). 📞
- **Location Tracking**: Get real-time GPS location of your dog. 🗺️
- **Feeding Notifications**: Set reminders for feeding intervals with customizable time settings (min. interval: 3 hours). ⏰

## 🧪 User Stories Analysis, Bug detecting, Inquiries and Gaps
- Before Starting to write a manual test cases I needed to analyze and verify user stories correctness and completeness
- **as in the First Sheet in the My Dog App TestCases and User Story Inquires, Gaps.xlsx file** 

## 🧪 Manual Testing Overview
- Then started the process of manual testing for the My Dog App. Below are key aspects of the testing process:
- **as in the second Sheet in the My Dog App TestCases and User Story Inquires, Gaps.xlsx file** 

## 📝 Test Scenarios
- Registration: Test the registration process using valid and invalid inputs.
- Dog Calling: Validate calling functionality while ensuring Bluetooth connectivity.
- Location Retrieval: Verify the accuracy of location data when GPS is enabled.
- Feeding Notifications: Test notification functionality for different feeding intervals.

## ✅ Positive Test Cases
- Successful registration with valid credentials and dog information. ✅
- Calling the dog when within Bluetooth range. 🎉
- Retrieving the dog's location when GPS is enabled. 📡
- Receiving feeding notifications at the specified intervals. 🕒

## ❌ Negative Test Cases
- Handling invalid email formats during registration. ❌
- Calling the dog when out of Bluetooth range. 📉
- Attempting to get the dog's location when GPS is disabled. 🚫
- Setting invalid feeding intervals (less than 3 hours). ⏳

## 📜 License
- **This project is licensed under the MIT License - see the LICENSE file for details.**