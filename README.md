# Salon Appointment Database

## Overview

This project is a Bash script designed to manage appointments for a salon. It interacts with a PostgreSQL database to handle customer information, available services, and appointment scheduling.

## Script

The script (`salon.sh`) provides a user interface for customers to select services, input their phone number and name, and schedule appointments.

## Database Schema

The database consists of the following tables:

- **customers**: Stores customer information, including their unique ID, phone number, and name.
- **services**: Contains information about available salon services.
- **appointments**: Records each appointment made, including the customer ID, service ID, and appointment time.

## Dependencies

- PostgreSQL

## Usage

Execute the `salon.sh` script to interact with the salon appointment system and manage appointments in the database.

```bash
bash salon.sh
```
