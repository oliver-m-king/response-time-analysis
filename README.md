# response-time-analysis

The purpose of this project is to undertake an analysis of the time taken by 3 different teams to respond to emails received in their respective inboxes.
The response time is measured in working hours, with each team having unique working days and hours.

The raw data is a selection of 80,000 pairs of datetimes; the first is the time and date the email was received, and the second is the time and date the email was responded to.

A list of public holidays is scraped from https://www.employment.govt.nz/leave-and-holidays/public-holidays/public-holidays-and-anniversary-dates/dates-for-previous-years/ using the request and BeautifulSoup libraries.
