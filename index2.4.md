1. Aim

The aim of this assignment is to identify and fix errors in an HTML file, inspect the webpage using browser DevTools, validate the HTML markup, and write clean and properly indented code.

2. Before Code (Buggy HTML)

The following HTML code contains missing closing tags, incorrect nesting, and missing attributes.

File name: before.html

<!DOCTYPE html>
<html>
<head>
    <title>My Introduction Page</title>
</head>
<body>
    <h1>Welcome to My Page
    <div>
        <h2>About Me</h2>
        <p>Hello! My name is Shubham Yadav.
        <p>I am a B.Tech CSE student.</p>
    </div>
    <div>
        <h2>My Skills</h2>
        <ul>
            <li>HTML
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>
    </div>
    <img src="profile.jpg">
    <a href="https://www.google.com">
        Visit Google
    <p>This is my introduction webpage.</p>
</body>
</html>

3. Errors Identified

The following errors were found in the buggy HTML file:

The <h1> heading does not have a closing </h1> tag.

The first paragraph does not have a closing </p> tag.

The first list item does not have a closing </li> tag.

The <a> anchor element does not have a closing </a> tag.

The image element is missing the alt attribute.

The HTML code is not consistently indented.

Some elements are not properly closed, making the code difficult to read and maintain.

4. Inspecting the HTML Using Browser DevTools

Open the buggy HTML file in Google Chrome.

Right-click anywhere on the webpage and select Inspect.

Open the Elements panel.

Inspect the HTML structure and check how the browser interprets the markup.

Look for missing tags and unexpected element nesting.

Observation: Browser DevTools helps us inspect the DOM structure. However, browsers may automatically correct some HTML errors, so the Elements panel may not show the original mistakes exactly as written.

5. HTML Validation

The HTML markup can be checked using the official W3C Nu HTML Checker.

Website: https://validator.w3.org/nu/

Steps:

Open the HTML validator website.

Select the option to validate by direct input.

Copy and paste the buggy HTML code.

Click the validation button.

Review the reported errors and warnings.

Correct the code and validate it again.

Observation: The validator helps identify markup errors and accessibility-related issues, such as a missing alt attribute on an image.

6. After Code (Corrected HTML)

File name: index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Introduction Page</title>
</head>
<body>
    <header>
        <h1>Welcome to My Page</h1>
    </header>

    <main>
        <div>
            <h2>About Me</h2>
            <p>Hello! My name is Shubham Yadav.</p>
            <p>I am a B.Tech CSE student.</p>
        </div>

        <div>
            <h2>My Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>
        </div>

        <div>
            <h2>My Profile</h2>
            <img src="profile.jpg" alt="My profile photo" width="200">
        </div>

        <div>
            <a href="https://www.google.com">Visit Google</a>
            <p>This is my introduction webpage.</p>
        </div>
    </main>
</body>
</html>

Note: Keep profile.jpg in the same folder as index.html, or replace the filename with the path to your actual image.

7. Result

The HTML file was debugged and corrected by fixing missing closing tags, improving the document structure, adding the required attributes, and formatting the code with proper indentation. The corrected webpage can be inspected using browser DevTools and checked with the W3C HTML validator.

8. Screenshots for Submission

Attach the following screenshots to your assignment:

Before Screenshot: Open before.html in Chrome and capture the webpage.

DevTools Screenshot: Show the Elements panel while inspecting the HTML structure.

After Screenshot: Open index.html in Chrome and capture the corrected webpage.

Validation Screenshot: Show the corrected HTML in the W3C validator after checking it.

Conclusion

This assignment helped me understand how to identify and fix HTML errors, use browser DevTools to inspect webpage elements, validate HTML markup, and write clean, readable, and properly structured HTML code.