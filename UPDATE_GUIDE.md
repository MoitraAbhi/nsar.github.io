# Update the existing GitHub Pages website

1. Extract WebLab.zip and open the WebLab folder.
2. Open your existing website repository on GitHub.
3. Select Add file → Upload files.
4. Drag the files and folders inside WebLab into the upload area. Keep index.html
   at the repository's top level. Preserve the images/collaborators folder path.
5. Commit the changes to the branch used by GitHub Pages, normally main.
6. Wait for the Pages deployment to finish, then refresh your website.

No new repository or build command is needed. The existing Pages settings can
stay as they are. Upload the extracted contents rather than the ZIP itself.

## Included changes

- Full lab name on the homepage and in the shared footer.
- NSAR branding in navigation and browser titles throughout the website.
- A brief homepage overview about device–architecture–algorithm co-optimization.
- The homepage Latest News section removed.
- Six locally bundled collaborator logos with links to their organizations.
- Responsive styling for the new name and collaborator section.
- The two existing Join Us navigation filenames corrected.

To edit the homepage text later, open index.html. Collaborator display settings
are grouped near the end of styles.css. See LOGO_SOURCES.md for asset sources.
