# SWE645-Assignment-1-HTML-AWS-S3

This assignment contains:
1) A index.html page - Has my personal Introduction page with a picture and breif description about myself. A class homepage. 
2) A error.html - Used to render a message in case main page is not availale for any reason.
3) A form.html - It has a student survey form made keeping in mind all the requirements mentioned on the assignemnt question.
Facility given to navigate from home page to the Student survey page. 

4) An assets folder - which contains images, files and the external stylesheets used for this assignment.
5) A readme.md file

Please check out my assignment below hosted on AWS S3 bucket: 



You can view my homework assignment 1 using above is the link. Both pages (Index and Survey Page) along with their CSS files and other media are uploaded to the AWS S3 bucket.

Steps followed to host on AWS S3:
1) Created an AWS free tier account and created a S3 bucket. Unchecked the disable public access while doing so.
2) Under properties - enable static website hosting and save changes
3) under permissions - enable public access and add bucket policy wherein added bucketname under Resource (from the tutorial given)
4) Uploaded all files mentioned above to the bucket created
Tested the above link and is working.