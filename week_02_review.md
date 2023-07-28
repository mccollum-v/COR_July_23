## Git Commands:

1. `git init`: Initialize a new Git repository in the current directory.
2. `git clone <repository_url>`: Clone a remote repository to your local machine.
3. `git add <file>`: Add a specific file to the staging area.
4. `git add .`: Add all changed files to the staging area.
5. `git commit -m "commit message"`: Commit the changes in the staging area with a descriptive message.
6. `git status`: Show the current status of the repository (changed files, staged files, etc.).
7. `git log`: Display the commit history.
8. `git pull`: Fetch and merge changes from the remote repository to your local branch.
9. `git push`: Push your local commits to the remote repository.
10. `git branch`: List all branches in the repository.
11. `git branch <branch_name>`: Create a new branch.
12. `git checkout <branch_name>`: Switch to a different branch.
13. `git merge <branch_name>`: Merge a branch into the current branch.
14. `git remote -v`: Show the remote repositories linked to your local repository.

## GitHub:

1. **Creating a Repository on GitHub:**
   - Log in to GitHub and click the "New" button to create a new repository.
   - Name your repository, add a description (optional), and choose visibility options (public or private).
   - Click "Create repository" to finalize.

2. **Connecting Local Repository to GitHub:**
   - If you have NOT run the git init command, follow these steps:
     1. Copy and paste the first codeblock shown on the create new repo page. This initializes your local repository.
   - Otherwise, follow these steps:
     1. Type `git init` in the terminal to initialize a new Git repository in the current directory.
     2. Add your existing code to the staging area with `git add .`.
     3. Commit the changes with a descriptive message using `git commit -m "message"`.
     4. Push your changes to GitHub using `git push`.
     5. Now, copy and paste the second codeblock from the create new repo page. This will add the remote repository URL to your existing local repository.
 
3. **Pushing to GitHub:**
   - After committing your changes locally, use `git push` to send your commits to GitHub.

## HTML:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>Heading</h1>
    <p>This is a paragraph.</p>
    <a href="https://www.example.com">Link</a>
    <img src="image.jpg" alt="Image">
</body>
</html>
```

- `<!DOCTYPE html>`: Defines the document type and version.
- `<html>`: The root element of the HTML document.
- `<head>`: Contains meta-information about the document.
- `<title>`: Sets the title of the webpage shown in the browser.
- `<body>`: Contains the visible content of the webpage.
- `<h1>`, `<p>`, `<a>`, `<img>`: Basic HTML elements for heading, paragraph, link, and image, respectively.

## Basic CSS:

```css
/* Selectors and Styles */
h1 {
    color: blue;
    font-size: 24px;
}

p {
    color: #333;
    font-size: 16px;
}

/* Classes and IDs */
.button {
    background-color: green;
    color: white;
    padding: 10px;
}

#header {
    background-color: lightgray;
}

/* Combining Selectors */
h1, p {
    font-family: "Arial", sans-serif;
}
```

- Use `selector { property: value; }` to apply styles to HTML elements.
- You can use element names (e.g., `h1`, `p`) or assign classes (e.g., `.button`) and IDs (e.g., `#header`) to target specific elements.
- Multiple selectors can share the same styles, as shown with `h1, p`.
- CSS properties like `color`, `font-size`, `background-color`, and `font-family` modify the appearance of elements.

## CSS Game Solutions - Video Walkthroughs

1. **CSS Diner**
   - See the video walkthrough here: [CSS Diner Walkthrough](https://www.youtube.com/watch?v=SbYdwj5lito)

2. **FlexBox Froggy**
   - See the video walkthrough here: [FlexBox Froggy Walkthrough](https://www.youtube.com/watch?v=8z8G_bN3qrw)

3. **Flexbox Defense**
   - See the video walkthrough here: [Flexbox Defense Walkthrough](https://www.youtube.com/watch?v=JrQ0OoQyWWk&t=568s)



