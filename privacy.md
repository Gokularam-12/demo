Privacy Policy --- LeadConnectPoC
Last updated: November 12, 2026

LeadConnectPoC is a demonstration project built to show how test leads
submitted through Meta Lead Ads forms can be delivered to a React Native
application in real time.
Information We Process
When a test lead is submitted, the project may process information
entered in the form, such as:
- Full name
- Email address
- Phone number, if included in the form
- Other form fields and Meta lead identifiers
For this proof of concept, please use dummy/test information only. Do
not submit sensitive personal information.
How Information Is Used
Information is processed only to demonstrate the lead-delivery workflow:
1. Meta sends a lead notification to the project's backend webhook.
2. The backend retrieves the lead details from Meta using the
   configured Page access token.
3. The backend sends the lead to connected React Native app clients in
   real time.
The project does not use submitted information for advertising,
marketing, profiling, or selling data.
Storage and Sharing
This proof of concept does not intentionally save leads to a database.
Lead details are transmitted to connected app clients and may be present
temporarily in application memory or development-server logs while the
project is running.

Lead information is not intentionally shared with third parties by this
project. Meta processes information according to its own terms and
privacy policy.
Data Security
This is a development and demonstration project, not a production
lead-management service. Do not use it to submit real customer
information. Access tokens and other credentials should be kept private
and stored in environment variables, never committed to a public
repository.
Data Retention and Deletion
The project does not provide a permanent lead-storage facility. Data
held in application memory is cleared when the relevant process is
stopped. Any development logs should be deleted when no longer needed.
Contact
For questions about this demonstration project or this privacy policy,
contact the repository owner through the GitHub repository where
LeadConnectPoC is published.
