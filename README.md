# Student Class Web Page and CS Department Information

This is a project I did in my university.

## Part 1: Student Class Web Page

### Project Overview
Welcome to the Student Class Web Page project! In this assignment, I created my own class homepage and hosted it on mason.gmu.edu. The page features a picture and a brief description of myself, enhanced with a W3.CSS Template for an appealing look and feel.

### Mason Web Page Setup
Followed the instructions to create the Mason web page:

1. **Connect to Mason Server:**
   - Used an SSH client (WinSCP for Windows / Cyberduck for MacOS) to transfer files (SFTP) from my local computer to mason server.
   - For connection details, referred to [Mason SSH Guide](http://labs.ite.gmu.edu/index.php/FAQ/SSH).

2. **Navigate to Home Directory:**
   - `cd` // Go to my home directory

3. **Make Home Directory Readable:**
   - `chmod 711 .` // Made my home directory readable

4. **Create Public HTML Directory:**
   - `mkdir public_html` // Created the standard home page directory

5. **Make Public HTML Directory Readable:**
   - `chmod 711 public_html` // Made the directory readable

6. **Navigate to Public HTML Directory:**
   - `cd public_html` // Went to the home page directory

7. My URL is: [http://mason.gmu.edu/~your_username/](http://mason.gmu.edu/~your_username/)

### References
- [How to Set Up a Personal Site](https://its.gmu.edu/knowledge-base/how-to-set-up-a-personal-site/)
- [Web Development Knowledge Base](https://its.gmu.edu/knowledge-base/web-development/)

## Part 2: HTML5 and CSS

### CS Department Information Page and Survey Form

#### CS Department Information Page
- Brief description of the department using HTML heading elements.
- List of MS Degrees using HTML list elements.
- Required courses for each MS degree using a table.
- CS Department Survey Page featuring a form with text boxes, checkboxes, radio buttons, text areas, and a submit button.
- Use of datalist feature for high-school graduation month.
- Autocomplete attribute for the survey form.
- Placeholders for input fields with examples.
- Use of the required attribute for fields.
- Focus on the first text field when the form is opened.
- Dropdown list for likelihood of recommending the school.

#### Styling and Design
- Utilized the George Mason University color scheme.
- Used an embedded or external responsive CSS framework like W3.CSS.
- GMU Logo as an image link to the GMU Website fixed on the right-bottom.
- Custom styling for fonts, colors, background, etc.
- Heading inside a rectangular box with a solid border in GMU green (#006633) and a box-shadow.
- Light gray background for the body of the page.

### Deployment
Created a link to the CS Department Information Page along with the Student Survey Form on my class homepage. Posted the link on my [class web page](http://mason.gmu.edu/~your_username/).

### Useful Links
- [W3.CSS Documentation](https://www.w3schools.com/w3css/default.asp)
- [W3.CSS Templates](https://www.w3schools.com/w3css/w3css_templates.asp)
