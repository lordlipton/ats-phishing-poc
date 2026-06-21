# ATS Name Field PoC

## Overview
This was just the result of some research that I was doing on applicant tracking systems in major companies allowing email injection through the lack of sanitization in name fields. Essentially you are able to inject full paragraphs and URLS into first name feilds and then submit the application under another persons email meaning that they receive an official email with content partially created by you if crafted correctly. This could possibly lead to large scale phishing attacks just due to the trust factor that alot of these companies have inhearently with their domain. I thought it was a really interesting attack vector that I havnt really heard talked about and I found that most of the major companies in the world have this functionality. Bellow I created a little POC that you can test out how it works for yourself. If you wanna learn more I dropped a full research paper on it here ([Read the article on Medium](https://medium.com/@lordlipton/how-i-found-a-phishing-vector-hiding-in-a-fortune-50-company-email-and-what-it-says-about-trust-in-6f5f8c88beae)) that I had quite a bit of fun writing.

## Usage
1. Clone or download this repository.
2. Open `index.html` in a web browser.
3. Enter any value into the "Name" field.
4. Observe how the input appears in the simulated email section below the form.
