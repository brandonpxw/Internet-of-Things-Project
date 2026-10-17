# Internet of Things Project: Smart Gym Locker Security

A smart gym locker that can tell when it's being broken into. Members open their locker with
their own RFID card, a light sensor inside watches for intruders, and a buzzer and LEDs alert
staff the moment something's wrong.

**Nanyang Polytechnic · Year 3 · 2023** · [Portfolio page](https://brandonpxw.github.io/portfolioPages/iotp.html)

## How it works

| Part | What it does |
|---|---|
| Raspberry Pi 3 | Runs the locker and reads the sensors |
| RFID reader | Lets members unlock with their own RFID card |
| Light sensor | Detects the locker being opened without a valid card |
| Buzzer, red and green LEDs | Show access granted or denied, and sound the alarm |
| UART sensor | Another sensor connected to the Pi |
| SQL database | Stores the system's data for the app |
| Windows Forms app | Dashboard for members and admins |

The Windows Forms app covers the dashboard, account management, notifications, tickets, audit
logging, a booking system and registration.

## Built with

Raspberry Pi 3 · RFID · light sensor · Windows Forms · SQL

## About this repository

This repository holds the project summary only; the source code isn't published here.

## What I learned

This was my first time working with sensor technology, and it was an extremely fun and
rewarding project. The aim was to improve on the security of existing gym lockers.
