# Service Mapping Automation Project - Airtable & Make.com Integration

## 📌 Project Overview

Developed a comprehensive automated service mapping system that processes CSV uploads from multiple booking providers (**Boulevard**, **Vagaro**, and **Square**) and intelligently maps service data into a centralized **Airtable** database.  
This automation eliminates manual data entry and ensures consistent service categorization across different platforms.

---

## 🔧 Key Features & Functionality

- **Multi-Platform Integration**  
  Automatically detects and processes CSV files from three major booking providers, each with their unique data structures and formatting requirements.

- **Intelligent Service Mapping**  
  Built-in logic checks for existing service entries to prevent duplicates while automatically creating new service records for unmapped items—maintaining data integrity throughout the process.

- **Automated Workflow Processing**  
  Upon webhook trigger, the system retrieves upload records from Airtable, downloads attached CSV files, parses the data, and routes it through provider-specific processing pathways.

- **Dynamic Status Management**  
  Services are automatically tagged with mapping status (`MAPPED` / `UNMAPPED`) to facilitate easy identification of items requiring manual review or categorization.

---

## 🛠️ Technology Stack

- **Make.com** – for workflow automation and orchestration  
- **Airtable** – as the primary database and file storage solution  
- **Custom Webhooks** – for trigger-based processing  
- **CSV Processing Modules** – for data parsing and transformation  
- **Conditional Routing** – based on booking provider identification  

---

## 📈 Business Impact

This automation:

- Significantly reduces manual processing time  
- Ensures data consistency across multiple booking platforms  
- Provides a **scalable solution** for service management that can easily accommodate additional booking providers in the future
