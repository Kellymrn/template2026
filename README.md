# AR Explorer — MindAR Image Tracking Template
This educational template demonstrates how to create a simple web-based augmented reality (AR) experience using MindAR and Three.js. It recognizes three images (targets/markers) and displays a different 3D model with sound for each target. No installation is required for viewers: the experience runs in a compatible browser with camera permission. 
## Make your own copy (Fork)
1. Sign in to [GitHub](github.com).
2. Open the [template2026] repository(github.com/avartscourses/template2026).
3. Select Fork → Create a new fork.
4. Choose your GitHub account as the Owner; keep or change the repository name.
5. Select Create fork. You can now edit files in your own repository without changing the original.

A fork is a separate repository linked to the original. This is normal and does not give you permission to edit the original repository.

## Publish your project with GitHub Pages
1. Open your fork on GitHub.
2. Make sure index.html is in the repository's main (root) folder.
3. Go to Settings → Pages.
4. Under Build and deployment, choose Source: Deploy from a branch.
5. Select Branch: main (or your repository's default branch) and Folder: /(root), then Save.
6. When deployment finishes, select Visit site in the Pages settings.
Your URL will typically look like:

https://YOUR-USERNAME.github.io/REPOSITORY-NAME/

The site updates when you commit changes to the published branch. Publishing may take a few minutes.

## Run and test the AR experience
1. Open the GitHub Pages URL on a phone or computer with a camera.
2. Press Start AR and allow camera access when asked.
3. Point the camera at one of the three target images.
4. When the target is recognized, its 3D model appears and its sound plays.
5. Move the camera away: the target is lost and the sound is paused.
6. Press Stop AR to stop the session; press Start AR again to restart.
For reliable detection, use a clear printed or displayed target, sufficient lighting, and keep the whole target visible. Test all three targets, sound playback, and Start → Stop → Start.
Avoid opening index.html directly as a file:// URL. Use GitHub Pages or a local web server. Camera access normally requires HTTPS or localhost.

3D Model (*.gltf) + Ήχος (*.mp3)


