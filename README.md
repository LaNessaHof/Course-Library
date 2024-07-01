# Course Library

Welcome to the Course Library repository! This repository hosts an index page that provides an organized collection of educational courses. Each course is hosted on GitHub Pages and can be easily accessed through the provided links.

## Overview

The `course-library` repository is designed to serve as a central hub for various courses. Each course is represented by an image and a link that directs users to the specific course page.

## Repository Structure

The repository contains the following main components:

- `index.html`: The main page of the course library, listing all available courses with links and images.
- `README.md`: This file, providing an overview of the repository and instructions on how to use it.

## Adding Courses

To add a new course to the library:

1. **Host the Course**: Ensure the course files are hosted in a separate GitHub repository and that GitHub Pages is enabled for that repository.
2. **Update `index.html`**: Add a new entry to the `index.html` file in the following format:

   ```html
   <div class="course">
       <img src="https://LaNessaHof.github.io/course-repository-name/image.png" alt="Course Name">
       <a href="https://yourusername.github.io/course-repository-name" target="_blank">Start Course Name</a>
   </div>
