# Blockchain IoT For Freshfood

This is a repository for Fullstack Freshfood App:

<image src="/docs/images/background.png" style="background-color:#ffffff" alt="background"></image>

- Smart contract: Solidity, Hardhat, Infura
- Front-end: ReactJS, TailwindCSS, Google Maps, Pinata
- Back-end: NextJS, MongoDB, Sendgrid
- Mobile Application: Flutter
- IoT System: C/C++

Features:

- Smart contract deploy on Infura
- Back-end hash log data of product and storage it to Blockchain
- With Front-end:
  - Authentication with Metamask
  - All data of product storage on Blockchain
  - Create/Update product, in which image upload to Pinata
  - Transfer/Verify product
  - View product
  - Update log for product
  - Update infromation for IoT System
- With IoT System:
  - Connect to Blockchain
  - Collection location of product and storage location into Blockchain

### Capture

#### Webiste Application

1. Connect to Metamask
   ![Connect to Metamask](/docs/images/web-connect-to-metamask.jpeg)

2. Home page:
   ![Home page](/docs/images/web-home-page.jpeg)

3. Product page:
   ![Product page](/docs/images/web-product-page.jpeg)

- Transfer product:
  ![Transfer product](/docs/images/web-transfer-product.png)
- Verify product:
  ![Verify product](/docs/images/web-verify-product.png)

4. Dashboard page:
   ![Dashboard page](/docs/images/web-dashboard-page.jpeg)

5. Device page (to setup IoT devices):
   ![Device page](/docs/images/web-device-page.jpeg)

6. Tracking page:
   ![Tracking page](/docs/images/web-tracking-page.jpeg)

#### Mobile Application

#### IoT Hardware

### Prerequisites

**Node version 18.x.x**

### Cloning the project

- [Smart Contract](https://github.com/doankhietthanh/freshfood_contract)

```shell
git clone https://github.com/doankhietthanh/freshfood_contract_.git
```

- [Back-end](https://github.com/phamtanminhtien/freshfood-be)

```shell
git clone https://github.com/phamtanminhtien/freshfood-be.git
```

- [Website Application](https://github.com/phamtanminhtien/freshfood-fe)

```shell
git clone https://github.com/phamtanminhtien/freshfood-fe.git
```

- [Mobile Application](https://github.com/phamtanminhtien/freshfood_app)

```shell
git clone https://github.com/phamtanminhtien/freshfood_app.git
```

- [IoT System](https://github.com/doankhietthanh/freshfood-iot)

```shell
git clone https://github.com/doankhietthanh/freshfood-iot.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
VITE_APP_BASE_URL=
VITE_APP_CONTRACT_ADDRESS=
VITE_GOOGLE_MAP_API_KEY=
VITE_PINATA_JWT=
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
