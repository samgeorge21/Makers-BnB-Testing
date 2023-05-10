MAKERS B&B - EXPLORATORY TESTING

90 minute timeboxed testing: 10-15 min allocated for each testing area

1. Listing a space/spaces: adding/editing space information
2. Adding/editing availability
3. Requesting a space
4. Space availability display
5. Space no longer available
-------------------------

Test 1 purpose:

See whether it is possible to list a space with relevant information

Steps:

Log in
Navigate to 'List a Space' page
Fill in information fields (name, description, price per night, available from/to)
Click 'List my Space'

Data:

Name: Steve Stephenson
Description: A very spacious space
Price per night: £999
Available from/to: 25/12/2023 to 1/1/2024

Expected outcome:

Confirmation message (email alert) received to state space has been listed. Space is visible in Spaces page.
-------------------------

Test 2 purpose:

See whether it is possible to edit the available dates for a space.

Steps:

Navigate to Spaces page
Navigate to individual new space page
Specify some available dates
Confirm/submit

Data:

Available from/to: 25/12/2023 to 12/1/2024

Expected outcome:

Should redirect back to Spaces page with updated information. When I enter specific dates the property should be visible/not visible based on updated date ranges.
-------------------------


Test 3 purpose:

See if a space can be requested as a separate user/in a separate session.

Steps:

Log in as a new user
Enter desired date range in Spaces filter
Confirm that previously added space is visible and click on space
Submit a request for the available dates

Expected outcome:

Confirm request is listed under Requests I've made.
-------------------------

Test 4 purpose:

Confirm seller has received the request and can accept it.

Steps:

Log in as seller (following Test 3)
Navigate to Requests page
Navigate to individual request
Click on Confirm Request button

Expected outcome:

Request is showing on Requests page. Seller is able to confirm request.
-------------------------

Test 5 purpose:

Confirm dates of booked room are no longer showing as available to a new user.

Steps:

Log in as new user (following Test 4)
Navigate to Spaces page
Filter for date range previously used
Check if previously booked space is showing as an available space

Expected outcome:

User is not able to view previously booked space.
-------------------------