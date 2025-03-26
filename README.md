# HammelWmshi System Proposal

## Overview
The **HammelWmshi** project is a proposal for a new system to improve the operations of HammelWmshi, a virtual company offering local transportation services. The company operates a fleet of 50 vehicles classified into 5 categories by size and serves only registered business clients. This proposal addresses the limitations of the current system and introduces a streamlined, efficient solution.

## Background
### Current System
- The existing system is built in MS Access.
- Service requests are handled manually via phone, email, or fax, leading to inefficiencies and errors.
- Clients have expressed dissatisfaction due to slow processing, calculation mistakes, and high additional charges.
- Charges are based on the distance traversed and the weight of goods, with additional charges for extra distances, which are prone to miscalculation.

### Proposed System
The proposed system aims to:
- Automate and streamline the service request process.
- Reduce errors in calculations and improve client satisfaction.
- Introduce a web-based platform for clients to register and place service requests.

## Features
- **Client Registration**: Businesses can register online by providing details such as name, contact person, phone, email, company license, and address.
- **Service Requests**: Clients can log in to place service requests, specifying departure and destination addresses, type of goods, weight, volume, and urgency.
- **Vehicle Assignment**: The system automatically assigns the nearest available vehicle based on the type, weight, and volume of goods.
- **Distance and Charges Calculation**: The system calculates transportation charges and additional charges for extra distances.
- **Real-Time Notifications**: Alerts are sent to officers and drivers for confirmation and updates.
- **Reports Generation**: The system can generate various reports, including:
  - Bills report between two dates.
  - Vehicle usage report between two dates.
  - Client activity report between two dates.
  - Service request report between two dates.

## Workflow
1. **Client Registration**:
   - Clients register online and await confirmation from an officer.
   - Upon approval, clients receive a unique ID for logging in.

2. **Service Request**:
   - Clients log in and submit a service request via an online form.
   - The system assigns a serial number to the request and processes it.

3. **Request Processing**:
   - An officer confirms the request.
   - The system assigns a vehicle and calculates charges.
   - A bill is sent to the client for confirmation.

4. **Delivery**:
   - Once confirmed, the vehicle is dispatched.
   - The driver notifies the system upon delivery.

## Implementation Considerations
- **Vehicle Location Tracking**: Each vehicle will be equipped with a GPS device to ensure accurate location tracking and efficient vehicle assignment.
- **Web-Based Platform**: A user-friendly web platform will be developed for client interaction and system management.

## Conclusion
This proposal outlines a comprehensive solution to address the inefficiencies of the current system, ensuring faster processing, accurate calculations, and improved client satisfaction.
