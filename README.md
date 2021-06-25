# react-intercom
## Getting Started
```bash
git clone https://github.com/rmdhnsyahrul/react-intercom.git
cd react-intercom/
```

## Workstation
### Windows 64
install [node](https://nodejs.org/en/)

## Add Intercom
### Instal chat for visitor
```bash
window.intercomSettings = {
    app_id: "XXXXXX"
  };
```

### Instal chat for visitor
```bash
window.intercomSettings = {
    app_id: "XXXXXX",
    name: "Bob", // Full name
    email: "bob@mailinator.com", // Email address
    created_at: new Date() // Signup date as a Unix timestamp
  };
```
note:
- change your app id to integrate intercom web with your intercom admin in index.js

## Running the project
```bash
npm install
npm start
```
