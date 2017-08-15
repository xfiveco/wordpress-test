WordPress Test Project
======================

## Project brief
Create a jobs list page pointing to individual job pages and a simple apply form.

On the **jobs list** page, a job will consist of:
- title
- description (truncated to 25 words)

On the **job page**, there will be: 
- position title
- company department (eg. Finance, Marketing, etc.)
- picture with default dimensions of 900 x 600px
- whether the job is On-site or Remote
- job description (can be a couple of paragraphs)
- apply button pointing to the apply page

Make all fields required in the WordPress admin. 

**Apply page** will have a simple form with the following elements:
- subject - required input field which will be automatically prefilled with *Re: [position title]* based on which position the user arrived from
- email - required / input field
- CV - optional / file upload dialog
- cover letter - optional / textarea
- submit button

The form can be sent to an email address or stored internally in WordPress.

## Requirements
1. Use [Chisel](https://github.com/xfiveco/generator-chisel) and [ACF](https://www.advancedcustomfields.com/)
1. For the form you can use a form plugin of your choice
1. Add some minimal styling and make the pages responsive according your best judgement.
1. Make the pages the smallest possible size - optimize images, disable jQuery or any other unnecessary scripts/stylesheets, etc.
1. Set up a virtual host with your project repository name (eg. *yourname-wp-test.dev*) so we don't have search & replace URLs when testing your project
1. Store the whole WordPress installation into the test repository and also store a database dump to it. 

## Project Deadline
Take your time but try to deliver it within 2 weeks time. If we don't see any activity in your test repository after 2 weeks (at least initial commits), we will automatically withdraw your application.
