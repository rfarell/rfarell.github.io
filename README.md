# Ryan Farrell's GitHub Website
Welcome to my personal website! Here, you can learn more about my research interests and projects, as well as find links to my social media and professional profiles.

The website is hosted at https://users.oden.utexas.edu/~rfarell/ and is built using HTML and CSS. The website files are organized as follows:

```
├── README.md
├── RyanFarellHiking.JPG
├── icon_LinkedIn.png
├── index.html
└── style.css
```

- README.md: This file, containing information about the website and its contents.
- RyanFarellHiking.JPG: A photo of me hiking, used as a background image on the website.
- icon_LinkedIn.png: An icon of my LinkedIn profile, used as a link on the website.
- index.html: The main HTML file for the website, containing the content and structure of the website.
- style.css: The CSS file for the website, containing the styling and layout information.

## Updating the Website
To update the website, you can use the scp command to copy the updated files to the server where the website is hosted. Here is an example of how to do this:

```
scp -r . rfarell@login1.oden.utexas.edu:public_html
```

Note that this command will replace the existing files on the server, so make sure to have a backup of any important data before running this command.

For more information on hosting a website at the Oden Institute, please see the Oden Institute Web Services documentation.