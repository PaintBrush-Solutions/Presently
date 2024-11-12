Presently
=========

Presently is a web-based tool designed to make creating interactive presentations with **impress.js** straightforward and accessible. impress.js is a powerful presentation framework, but it has a steep learning curve. Presently simplifies the process by allowing users to create presentations using markdown format, which it then converts into a polished, template-driven impress.js presentation with engaging animations and transitions.

Project Overview
----------------

Presently allows users to focus on content creation rather than coding by providing structured markdown input. Users can choose from a range of pre-built templates inspired by traditional presentation tools like PowerPoint. The tool handles all layout, transition, and animation settings automatically, making it easy for anyone to create professional-looking presentations.

Key Features
------------

- **Markdown-Based Input**: Presently uses markdown syntax to structure content, including titles, subtitles, images, and descriptions.
- **Template Options**: Offers a selection of pre-built templates for various presentation styles, eliminating the need for HTML/CSS coding.
- **Automatic impress.js Conversion**: Converts markdown content into a functional impress.js presentation with transitions and animations.
- **Error Handling**: If the markdown input does not follow the required structure, Presently will ignore the data and display a warning to the user.

Supported Templates
-------------------

Presently supports several standard slide templates, defined in markdown:

1. **Title Slide**: Specified with a level-1 heading, displayed as the main title.
2. **Intro Slide**: Main title as a level-1 heading and a subtitle as a level-3 heading.
3. **Content Slide**: Can include:
   - Main title (level-1)
   - Subtitle (level-3)
   - Image (link with caption)
   - Description (plain text)
4. **Picture Slide**: Includes a main title, picture, picture caption, and description.

Development Environment
-----------------------

- **Languages/Frameworks**: The project is developed using JavaScript, with a preference for the React framework on the front end.
- **Git-Based Workflow**: A Git-based workflow will be used, with pull requests (PRs) for all contributions. Each PR will be reviewed against the established acceptance criteria.

Getting Started
---------------

1. **Clone the Repository**::

   git clone https://github.com/YourOrg/Presently.git

2. **Install Dependencies**:
   - Run ``npm install`` to install necessary packages.

3. **Environment Setup**: Configure any additional environment variables needed for the project. See `docs/SETUP.md` for details.

For further instructions and detailed setup guidelines, please refer to the project’s documentation in the `/docs` folder.

Contributing
------------

We welcome contributions! Please adhere to the established code standards and provide descriptive commit messages. Any new features or improvements should be discussed with the team in advance. See `CONTRIBUTING.md` for more details.

License
-------

This project is licensed under the MIT License. See `LICENSE` for more details.
