# Lab8-Starter

Members: Trey Shneour

GitHub Pages URL: https://github.com/tshneour/Lab8-Starter

## How are graceful degradation and service workers related?
Graceful degradation is the design principle that a system should retain at least some functionality when service or parts of the software become unavailable. Essentially, you start with your fully-featured website then work your way down from the functionality to the structure, accomodating any issues that may appear with lower-end devices. Service workers are scripts that intercept and cache network requests so that a website can keep running even when the network is down. Thus, service workers adhere to the philosophy of graceful degradation by ensuring the website keeps working even when service is interrupted.

![pwa](image.png)