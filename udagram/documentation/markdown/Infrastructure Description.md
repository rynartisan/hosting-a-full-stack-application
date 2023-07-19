# Infrastructure Description

**Udagram** is built on
the [3 tier architecture](https://en.wikipedia.org/wiki/Multitier_architecture#Three-tier_architecture) where there is a
presentation tier, application tier and data tier.

## System Architecture Diagram

The below image shows an overview of the system architecture:
![](../assets/System%20Architecture.drawio.png)

## System Tiers

### 1. Presentation Tier

The frontend **(Udagram Frontend)** is an angular project hosted on an S3 storage bucket.

### 2. Application Tier

The backend **(Udagram API)** is a NodeJs application that utilized Express framework.

### 3. Data Tier

The database is a Postgres (ver. 14.7).