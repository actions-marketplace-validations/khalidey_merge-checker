Link to forked repo: https://github.com/simonebonato/devops-course/tree/2022 

The files are located in the following directories:

•	./.github/workflows/merge_checker.yml

•	./tools/merge_checker.py

To demonstrate that the action works, we uploaded the files to the forked repo linked above, and we forked it again to another account where we will perform a PR that is going to be merged to activate the workflow.
At this point we created a PR with the same template used in the course to make proposals for the course, with the following fake information, and most importantly including our emails.
After the PR has been accepted, the merge_checker.yml has been triggered. Here we can see the actions that have been triggered on GitHub and the email we received.

![image](https://user-images.githubusercontent.com/63954877/161733352-c18bd46b-1797-447d-9976-3c91c87bac9b.png)

![image](https://user-images.githubusercontent.com/63954877/161733379-1a84b50c-4078-43a6-a606-85d2a14c7185.png)

As we can see from the email, the content is exactly the one contained in the PR body, and the calendar event is scheduled for the 3rd of May at 17pm, which is precisely the date for the deadline of Task 3.

![image](https://user-images.githubusercontent.com/63954877/161733419-42657e67-4375-425f-9481-270eb7f8f552.png)
