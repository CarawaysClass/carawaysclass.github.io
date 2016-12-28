# carawaysclass.github.io
The pages found in this repository are embeddable content segments used in conjunction with the Learning Management System (LMS) that I use at Lone Star College.  Currently, that is Brightspace (by D2L).  The reason why this content is being maintained in github vs. directly in the LMS is two-fold:  

1. Brightspace does not provide a private, reusable content item that can be shared across courses.  This results in my having to maintain multiple copies of repeating content like my "Instructor Info" page.  If I find that I need to make a change or update that content, I have to visit each instance in order to keep things updated and consistent.  
2. As institutions of learning are apt to do, there is a good chance that the LMS that we are currently using will someday change.  Preparing for that possibility, I am looking for ways that I can keep my course content LMS-agnostic.  This github repository provides an LMS-independent repository for this repeating content.  

## Usage  
If you want to embed any of the html pages found in this repo, you simply use an iframe in the D2L content module.  Here's the basic structure:  

&lt;p&gt;&lt;iframe src="https://carawaysclass.github.io/[specific-page-url]" width="600px" height="1200px"&gt;&lt;/iframe&gt;&lt;/p&gt;

...so if I want to embed the instructor-info.html page, I use the following:

&lt;p&gt;&lt;iframe src="https://carawaysclass.github.io/instructor-info.html" width="600px" height="1200px"&gt;&lt;/iframe&gt;&lt;/p&gt;

