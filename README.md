# Gesture-Controlled-Bot-with-TH-sensing-features

This project includes the control of a bot (designed for deploying in industries ) using hand gestures.I have used MPU6050 module to take the hand gesture readings and then sent this via nrf24l04 module.At receiver side,another nrf24l01 is present to receive that gyroscope sensor data and then using that value,motor driver L298N is used to drive all the 4 motors towards a certain direction.

In 2nd part,NodeMCU has been used and an android app using MIT app inventor has been built.Firebase has been used for linking NodeMCU with our app.This bot is capable of sending Temperature and Humidity data back to the user via NodeMCU to an android application.Hence,user can monitor the temperature and humidity of the highly sensitive regions in the industry dedicated for production purposes only,especially where no living organisms are allowed to enter due to risk of contaminating the highly sensitive products.
