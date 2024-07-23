# Fynd Odoo Connector Extension

This extension facilitates seamless data synchronization between the Fynd platform and the Odoo platform. It ensures that customer records, product records, and order records are accurately and efficiently transferred.

## Features

- **Customer Records Sync**: Automatically syncs customer data from Fynd to Odoo.
- **Product Records Sync**: Keeps product information updated between both platforms.
- **Order Records Sync**: Ensures order details are consistent across Fynd and Odoo.

## Note 

- before syncing any order to odoo, please sync the customer and product first.
- The frontend is integrated into the same server.

## Technology Stack

- **Backend**: Node.js with Express
- **Frontend**: React integrated into the same server

### Run the Application

To start the application for development, use the following command:
```bash
npm run start:dev
```

# fynd-odoo
Node 14

## Project setup
```
npm install
```

### Compiles and minifies for production
```
npm run build
```

### To start react development server
```
npm run serve
```

### To start backend server to launch extension
```
npm run start
```
