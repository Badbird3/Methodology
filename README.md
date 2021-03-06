# App Pentest Methodology

### Argument for a Methodology
- Provides consistency
- Success is measurable 
- Provides reassurance for the client

1. Configure browser.
    - Install Firefox, Chrome, Chromium or similar. If already installed, clear all data
    - Install the following extensions: [Session box](https://sessionbox.io/), [Foxy proxy](https://getfoxyproxy.org/), [Wappalyzer](https://www.wappalyzer.com).  

2. While proxying traffic through Burpsuite, use the application as a normal user would to populate Burpsuite with data. 

3. IF the scope is small, copy over every endpoint to the excel sheet and audit each endpoint. 

4. IF the scope is large, identify endpoints that interact with critical functionality. Copy those endpoints to the excel sheet and audit each endpoint. 

5. Record and report issues
