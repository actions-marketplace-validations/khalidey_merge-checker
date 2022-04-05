# merge-checker

The following action is made to be used in the https://github.com/KTH/devops-course course and can only be used in that context. The 'merge-checker' Github action is an automatic email of PR merge success and calender event.

The following GitHub action automatically generates an email confirmation that notifies the students with the details of their PR (title, description, deadline) and additional information (who and when accepted the PR), when it is merged in the main branch.

The github action does the following:

- On merge, parses the PR description and determine its details.
- Writes an email that contains a calendar event for the date of the deadline at 17pm if the deadline was written correctly in the body of the PR (it contains "task #"), otherwise it only includes the PR details and the info regarding who accepted the PR.
- Sends an email w/details to parsed addresses.

This action could be very useful in order to give the students a confirmation that their request has been accepted and a further reminder about the deadline of their intended task with a calender event.
