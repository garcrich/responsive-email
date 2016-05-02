# Responsive HTML Email Mockup

The objective of this project was to code an email mockup provided by a graphic designer.

# Requirements

1.	Code a mockup of a PNG image in HTML that meets email standards.
2.	Make mockup responsive.

# Email Layout

Each section has been labeled with a comment which is separated from the previous comment by providing an empty line of code before it. This is for readability as and providing simplicity for reuse for future emails. The email layout from top to bottom is as follows:

1.	Header Container Table – Encapsulates header contents.
    *	Hidden Preheader – Used to display message for the description area of email headline before the user opens an email.
    *	Logo – Logo will center when width is 600px or less. Only effective on email clients that allow responsive CSS styles.

2.	Body Container – Encapsulates Body Content
    *	Heading –Equivalent to `<h1>` heading.
    * 	Main Content – Set up as a two column layout. Left and right columns have been specified with comments in the code. Columns will collapse when the screen width is 600px or less. Only effective on email clients that allow responsive CSS styles.
    *	CTA Button – made to be compatible with MS Outlook.
    *	Secondary Content – paragraphs have been specified with comments in the code.
    *	Complimentary Close – Consists of goodbye text followed by company logo.

3.	Footer
    *	Rules and Regulations
    *	Can-Spam Act Requirements – All Emails must include this information to be in compliance.
       1.	Recipient/Opt out option.
       2.	Apt Marketing Address.
    *	Copyright – Copyright info from Apt Marketing.

# Support

Despite varying standards for email clients, measures have been taken to improve standardization between email clients. Specific code comments have been added to provide specific information. Email clients optimized include:

*	Outlook – remove default padding
*	Windows phone 8 – prevent changing default text sizes, meta tag added for responsiveness
*	Hotmail – ensure full width display
*	Yahoo – attribute method used for CSS styles
*	Google – Styles written inline
*	Internet Explorer -- `-ms-interpolation-mode: bicubic;` added for smoother rendering

# Testing

Code was tested with Mail Chimp and Email on Acid. Minor changes were made to the button and the background style tag was moved from the body tag to the cell of the wrapper table for better cross browser support.