# Horiseon Accessibility Refactoring

Web accessibility is an increasingly important consideration for businesses. It ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also good for business for many reasons, one of them being that accessible sites are better positioned in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities can't access their website.

The challenge is to refactor the existing website code for best practices with a focus on accessibility.

## Links
* Live Site: https://joshualintz.github.io/horiseon-refactor/
* Code Repo: https://github.com/joshualintz/horiseon-refactor 

## Built With
* HTML
* CSS

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards:

* WHEN I view the source code, THEN I find semantic HTML elements
* WHEN I view the structure of the HTML elements, THEN I find that the elements follow a logical structure independent of styling and positioning
* WHEN I view the image elements, THEN I find accessible alt attributes
* WHEN I view the heading attributes, THEN they fall in sequential order
* WHEN I view the title element, THEN I find a concise, descriptive title

## Additional Notes

Overall, I felt the HTML code was acceptable but lacked best-practices, relying mostly on non-semnantic elements. I also felt the code was difficult to read priomarily due to a lack of comment tags and a logical flow. The images also lacked alt tags where necessary. Lastly, I modified the CSS file with single line comments and ordered the classes within the stylesheet by logical section, which promotes easier maintenance. There was also some consolidation of classes in efforts to respect the principles of DRY. 

## Grading Requirements

* Technical Acceptance CriteriaL: 40%
    * Satisfies all of the preceding acceptance criteria plus the following code improvements:
        * Application's links all function correctly.
        * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.
        * Application's CSS file is properly commented.
* Deployment: 32%
    * Application deployed at live URL
    * Application loads with no errors.
    * Application GitHub URL submitted.
    * GitHub repository that contains application code.
* Application Quality:  15%
    * Application resembles (at least 90%) screenshots provided in challenge instructions.
* Repository Quality: 13%
    * Repository has a unique name.
    * Repository follows best practices for file structure and naming conventions.
    * Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
    * Repository contains multiple descriptive commit messages.
    * Repository contains quality README file with description, screenshot, and link to deployed application.

## How to Submit the Challenge
* The URL of the deployed application.
* The URL of the GitHub repository that contains your code. Give the repository a unique name and include a README file that describes the project.
