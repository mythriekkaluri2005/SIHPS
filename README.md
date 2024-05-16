# Smart India Hackathon Workshop
# Date:16-05-24
## Register Number: 212223240034
## Name: E.Mythri
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea

To tackle the growing challenge of e-waste management, we propose the development of an integrated digital platform that facilitates the proper disposal and recycling of electronic devices. This platform will not only provide users with information on nearby e-waste collection and recycling facilities but also educate them on the environmental and health impacts of improper disposal. Additionally, it will incentivize responsible disposal through a credit points system based on the recovery of precious metals from disposed devices.

## Proposed Solution / Architecture Diagram
![ewaste](https://github.com/mythriekkaluri2005/SIHPS/assets/150231422/d718dcec-4b0f-4b71-a536-2b1c1ac077d4)


## Use Cases
![eeeeee](https://github.com/mythriekkaluri2005/SIHPS/assets/150231422/93c0fbec-eac5-40f8-96a6-98aaab390f00)



## Technology Stack
Frontend: React.js app with integrated Leaflet.js for mapping.
Backend: Node.js server using Express, connected to a PostgreSQL database.
API Integration: Google Maps API for detailed mapping and location services.
Deployment: Dockerized application hosted on AWS with auto-scaling.
CI/CD Pipeline: GitHub Actions for automated testing and deployment.
Monitoring: Grafana dashboard displaying metrics from Prometheus.


## Dependencies
Data Sources: Access to a reliable database or API containing information about e-waste recycling facilities worldwide.

Mapping Services: Integration with mapping services to display facility locations and provide directions.

User Reviews: Implementing a review system would require mechanisms for users to submit and display reviews, as well as moderation features to manage content.

Legal Compliance: Ensuring compliance with local regulations regarding e-waste recycling and data privacy laws.

Maintenance: Regular updates and maintenance to keep the database of facilities current and accurate.

