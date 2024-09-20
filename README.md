# Flash Cross-Domain Policy PoC

This repository demonstrates a proof of concept (PoC) for a cross-domain policy vulnerability found in `https://www.oneplus.in`.

## Description

The `crossdomain.xml` file from OnePlus allows all domains to access resources, which poses a security risk. This PoC illustrates how a malicious site can access data from the vulnerable domain.

## How to Run

1. Clone this repository or download the files.
2. Open `index.html` in a web browser that supports Flash.
3. Observe the console for any data received from `https://www.oneplus.in`.

## Note

Ensure you have permission to perform any testing and adhere to ethical guidelines. This PoC is for educational purposes only.
