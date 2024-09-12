# SCIM-Sample

This repository contains a simple Python application that demonstrates how to implement directory synchronization using the SCIM 2.0 protocol with Okta. The app provisions and syncs user data between Okta and a custom application.

## Features

- User provisioning (create, update, delete) via SCIM API - _currently one way sync works_
- Basic authentication for secure SCIM requests
- Supports SCIM `/Users` endpoint for managing user identities
- Syncs user information like username and email between Okta and the custom app

## Prerequisites

To run this project, you'll need the following installed:

- Python 3.x
- Flask
- SQLAlchemy
- Okta Developer Account (for generating SCIM API tokens)

## Setup
- Create an Okta Account, create a new SAML-based application, and enable provisioning. [Reference](https://support.okta.com/help/s/article/SCIM-Provisioning-Enabled-in-Custom-App?language=en_US)
- Clone the repository
- Run the application
- Assign a new user to the Okta application
- Notice the user being added to this application.
