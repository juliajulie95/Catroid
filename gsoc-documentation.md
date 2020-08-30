# GSoC documentation Julia Herold
My Summer of Code project was the redesign and implementation of the app's landing page.
At first I planned and designed the layout. The goal was to give the landing page a polished and user-friendly look, 
but also to incorporate the webview of https://share.catrob.at/app/.

### Landing page before my GSoC project:
![Screemshot](https://i.imgur.com/vgs4NYs.png)

### Concept for GSoC project:
![Concept](https://i.imgur.com/EKs08qk.png)
![Concept](https://i.imgur.com/ywsxbGv.png)

# GSoC Tasks

### 1. Project picture on the landing page
The picture of the last accessed project is shown on the landing page.  
Editing and uploading the project is implemented inside the picture as buttons.  
https://github.com/Catrobat/Catroid/pull/3645  
https://github.com/Catrobat/Catroid/pull/3698  
https://github.com/Catrobat/Catroid/pull/3699  

### 2. Floating action button
Instead of the "New project" button, I added a floating action button which saves space and is always visible, even when scrolling.  
https://github.com/Catrobat/Catroid/pull/3648

### 3. Refreshing of landing page after download
Because the landing page has a lot more functions now, we decided that it should update itself if changes happen.  
https://github.com/Catrobat/Catroid/pull/3742

### 4. Showing the last accessed projects
The 10 last accessed projects are now shown inside a horizontal scrolling widget, similar to the android play store.  
https://github.com/Catrobat/Catroid/pull/3755

### 5. Replace help button with toolbar icon
To get rid of the old help button, but make it always reachable, I added the button to the toolbar.  
https://github.com/juliajulie95/Catroid/commit/cca8ce301bcabd79f94feb60e509327fc94da3b7  
-> Finished but holding off merge until the next task is done, because this change alone would make the landing page too empty

### 6. Showing projects of the Share
Implementing of API calls for the featured projects and project categories of https://share.catrob.at/app/.  
Showing the featurend projects with their banners in a carousel.  
Showing the project categories in a horizontal scrolling view, like the projects on device.  
-> This task is not finished completely, but will be worked on in September as discussed with my mentors.

# Smaller tasks along the way:

### Replacing old .png assets with vector assets
https://github.com/Catrobat/Catroid/pull/3658

### Bugfixes 
https://github.com/Catrobat/Catroid/pull/3662  
https://github.com/Catrobat/Catroid/pull/3693  
https://github.com/Catrobat/Catroid/pull/3713  
https://github.com/Catrobat/Catroid/pull/3741  

### Updating all launcher icons
https://github.com/Catrobat/Catroid/pull/3726

