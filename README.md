# Problem Set 8

Start Date and Time| Due Date and Time | Cut-off Date and Time |
---|---|---|
10:50:00 AM on November 1, 2019 | 11:59:59 PM on November 7, 2019 | 12:00:00 AM on November 15, 2019 |

## Problem 8.1: Homepage
Build a simple homepage using HTML and CSS.

The Internet has enabled incredible things: we can use a search engine to research anything imaginable, communicate with friends and family members around the globe, play games, take courses, etc. The ability of the Internet we enjoy on an everyday basis is nearly all built on three core languages, each of which serves a slightly different purpose:

1. HTML, or HyperText Markup Language, which is used to describe the content of websites.

2. CSS, Cascading Style Sheets, which is used to describe the aesthetics of websites.

3. JavaScript, which is used to make websites interactive and dynamic.

Focusing on just the first two of those three languages, for now, create a simple homepage that introduces yourself, your favorite hobby or extracurricular, or anything else of interest to you.

Use the template `index.html` and `styles.css` files included in this problem set. Use `http-server` from the class to run and test your homepage. Make sure that you are in the right directory when executing `http-server` to serve your homepage. Chrome DevTools can be useful in analyzing your homepage.

### Specification
Implement in your homepage directory a website that must:

- Contain at least three different `.html` pages, at least one of which is `index.html` (the main page of your website), and it should be possible to get from any page on your website to any other page by following one or more hyperlinks (`<a>`).

- Use at least ten (10) distinct HTML tags besides `<html>`, `<head>`, `<body>`, and `<title>`. Using some tag (e.g., `<p>`) multiple times still counts as just one (1) of those ten.

- Integrate one or more features from Bootstrap into your site. Bootstrap is a popular library (that comes with lots of CSS classes and more) via which you can beautify your site. See [Bootstrap’s documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/) to get started. To add Bootstrap to your site, it suffices to include the following line of code in your pages' `<head>`:  

		<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">

- Have at least one stylesheet file of your own creation, `styles.css`, which uses at least five (5) different CSS selectors (e.g. tag (`example`), class (`.example`), or ID (`#example`)), and within which you use a total of at least five (5) different CSS properties, such as `font-size`, or `margin`.

- Ensure that your site looks nice on browsers both on mobile devices as well as laptops and desktops.

- No need to include any JavaScript on your site for this problem set, unless so inclined.

### Testing
If you want to view how your site looks while you work on it, use the `http-server` command. You will be brought to a URL of the form:

	https://127.0.0.1:8080

127.0.0.1 is the loopback Internet protocol (IP) address, also referred to as the "localhost." The address is used to establish an IP connection to the same machine or computer being used by the end-user.

`http-server` will give you one more URL, which is based on your computer's real IP address. Use this URL (and not 127.0.0.1) to access and test your homepage on a mobile device. Both your computer and mobile device may need to be on the same network. 

Recall also that by opening Google Chrome DevTools, you can simulate visiting your page on a mobile device by clicking the phone-shaped icon to the left of **Elements** in the developer tools window, or, once the Developer Tools tab has already been opened, by typing `Ctrl`+`Shift`+`M` on a PC or `Cmd`+`Shift`+`M` on a Mac, rather than needing to visit your site on a mobile device separately!

### Assessment
#### Correctness
Your site’s correctness will be assessed based on whether you meet the requirements of the specification as outlined above, and whether your HTML is well-formed and valid. To ensure that your pages are, you can use the [W3Schools HTML Validator](https://validator.w3.org/#validate_by_input) service, copying and pasting your HTML directly into the provided text box. Take care to eliminate any warnings or errors suggested by the validator before submitting it!

#### Design
In considering the overall design of your site, we will take into account the following:

- The aesthetics of your site are such that it is intuitive and straightforward for a user to navigate.

- Your CSS has been factored out into a separate CSS file(s).

- You have avoided repetition and redundancy by "cascading" style properties from parent tags.

#### Style
It is incumbent upon you to indent and align your HTML tags cleanly, as based on the examples shown in Week 8’s lecture. Know also that you can create an HTML comment with:

		<!-- Comment goes here -->

but commenting your HTML code is not as imperative as it is when commenting code in, say, C or Python. You can also comment your CSS, in CSS files, with:

		/* Comment goes here */

### Hints
For fairly comprehensive guides on the languages introduced in this problem, check out the documentation for each on W3Schools.

- [HTML](https://www.w3schools.com/html)
- [CSS](https://www.w3schools.com/css)
- [JavaScript](https://www.w3schools.com/js)

## Grading Rubric
Description|Grade
---|---:|
Submitted all programs.|10%
No warning or error on all programs.| 10%
Programs are clean, understandable, commented and organized. | 10%
Thoroughly documented in *README.md* what the programs do. | 20%
Correctly implemented all programs.| 50%
**Total** | **100%**

## Submission Guideline
- Create a new GitHub project with the right name and problem set number (e.g., `LMSC261-ProblemSet1`).
- Commit and push Scratch files for this problem set into the newly created project.
- Submit the link to the repository on OL to complete the problem set.

## Submission policy:
- All problem set must be first committed and pushed to your GitHub repository. 
- The link to your repository must be submitted to OL to complete the problem set.
- Late projects will incur a penalty of 10% each day.
- Problem sets and projects are due by 11:59:59 pm on the date specified
- After 12:00:00 am (the next day after the due day), your problem sets/projects is one day late (-10%).
- After the next 12: 00:00 am cycle (two days after the due day), your problem sets/projects is two days late (-20%).
- Problem sets and projects will not be accepted after 12:00:00 am at one week after the deadline

---  
**Berklee College of Music**    
Liberal Arts Department  
LMSC-261: Introduction to Computer Programming  
Fall 2019