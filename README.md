# online-fashion-inventory-management
Team 9 - Online Fashion Inventory &amp; Warehouse Management System
# Online Fashion Inventory & Warehouse Management System

## Project Overview
The Online Fashion Inventory & Warehouse Management System is a web-based application designed to manage inventory across a central warehouse and multiple stores. It aims to maintain accurate stock quantities, support stock requests and transfers, prevent inconsistent inventory updates, and identify low-stock items.

## Project Information
- **Team Number:** 9
- **Project Theme:** Transaction-Based Inventory Management System
- **Guide:** Dr. Suvarna Kanakaraddi
- **Department:** Computer Science & Engineering
- **Sprint:** Sprint 1 — Solution Design and Selective Partial Implementation

## Problem Statement
Managing fashion inventory across multiple stores and a central warehouse can lead to inaccurate stock records, delayed stock requests, stock mismatches, and difficulty identifying low-stock products. This project proposes a centralized system to track SKU-wise stock, manage stock movement, maintain consistency, and provide inventory monitoring.

## Project Objectives
1. Maintain SKU-wise inventory for each store and warehouse.
2. Support stock addition, updating, and deletion.
3. Manage stock requests, approvals, reservations, dispatch, and receipt.
4. Prevent negative stock and over-allocation.
5. Identify low-stock items using configurable thresholds.
6. Maintain transaction history and transfer status.

## Main System Modules

### E1 — Inventory Management Engine
**Owner:** Darshan Jannu  
Maintains SKU details and location-wise stock quantities and supports stock addition, updating, and deletion.

### E2 — Stock Request & Transfer Engine
**Owner:** Shreya Yankanchi  
Manages stock requests, approval or rejection, reservation, dispatch, receipt confirmation, and transfer status.

### E3 — Stock Consistency Engine
**Owner:** Arpita Adavimath  
Validates stock transactions, prevents negative or over-allocated stock, and supports consistent updates and recovery from failed operations.

### E4 — Inventory Monitoring Engine
**Owner:** Trupti Hiremath  
Supports inventory search, low-stock detection, monitoring, and transaction-history tracking.

## Planned Scope
- User login and role-based access
- SKU and stock management
- Location-wise inventory tracking
- Stock request and transfer workflow
- Transaction validation and consistency
- Low-stock monitoring and history

## Out of Scope for the Initial Version
- Online shopping and payment processing
- Delivery GPS tracking
- Advanced demand forecasting
- Full ERP integration

## Sprint 1 Deliverables
- Overall system architecture
- Engine interaction and dependency design
- Engine-wise architecture
- End-to-end sequence diagram
- Database ER diagram and main table design
- Stock transfer workflow and state design
- Algorithms, interface, security, and testing plans
- Selective early implementation, where ready

## Technology and Tools
The final technology stack will be documented once the team confirms the specific programming language, web framework, database, and development tools.

## Current Status
**Sprint 1:** Solution design and planning. Implementation and testing status will be updated as actual work is completed.

## Team Members
- Trupti Hiremath — E4: Inventory Monitoring
- Shreya Yankanchi — E2: Stock Request & Transfer
- Arpita Adavimath — E3: Stock Consistency
- Darshan Jannu — E1: Inventory Management

## Repository Structure
- `docs/` — Project documents and design diagrams
- `src/` — Application source code, as development begins
- `tests/` — Test cases and test results, when available
- `README.md` — Project overview and setup information

*Note: Folder contents and implementation status should reflect the files and work actually completed by the team.*
