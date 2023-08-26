# Recyclo - E-Waste Recycling Project

![Recyclo Logo](/path/to/logo.png) <!-- Replace with the actual path to your logo image -->

Recyclo is a startup project dedicated to promoting the responsible disposal and recycling of electronic waste (e-waste). Our platform utilizes OpenStreetMap (OSM) data to create a seamless experience for users to efficiently recycle their e-waste. This README provides an overview of the Recyclo project, its features, and how to set up the application.


## Introduction

Electronic waste (e-waste) poses a significant environmental and health risk when not disposed of properly. Recyclo aims to bridge the gap between individuals wanting to recycle their e-waste and recycling centers that can handle the materials responsibly. Our platform provides users with the convenience of locating nearby e-waste deposit centers, requesting waste pickups, and contributing to a cleaner environment.

## Key Features

- **OpenStreetMap Integration**: We leverage OpenStreetMap (OSM) data to map our e-waste deposit centers, making it easier for users to locate their nearest center.Also we track the waste location as uploaded by the user in our admin panel using OSM.

- **User-Friendly Mobile App**: Our mobile app allows users to submit details about their e-waste, request pickups, and find the most convenient deposit centers.

- **Efficient Waste Collection**: Users can either drop off their e-waste at designated centers or request our team members to pick it up from their location.

- **Admin Dashboard**: The admin dashboard, built using React, offers an intuitive interface for managing e-waste pickup requests, optimizing routes, and monitoring recycling center activity.

- **Scalable Backend**: The backend API, developed using Django Rest Framework (DRF), handles user data, e-waste details, and communication between users and recycling centers.

## Getting Started

### Prerequisites

- Node.js and npm (for running the admin dashboard)
- Python and Django (for running the backend API)
- Mobile app development environment (for testing the mobile app)

### Installation

1. Clone the repository: `git clone https://github.com/your-username/recyclo.git`
2. Navigate to the project directory: `cd recyclo`

### Configuration

#### Backend (Django API)

1. Create a virtual environment: `python -m venv venv`
2. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
3. Install the required packages: `pip install -r requirements.txt`
4. Apply migrations: `python manage.py migrate`
5. Run the development server: `python manage.py runserver`


### Usage



## Contributing

We welcome contributions from the community! If you'd like to contribute to Recyclo, please follow our [contribution guidelines](CONTRIBUTING.md).



By participating in the Recyclo project, you're not only contributing to a more sustainable environment but also helping to spread awareness about responsible e-waste recycling. Thank you for being a part of our mission!
