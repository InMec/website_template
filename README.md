# Website to display multiple presentations in image format.

The website is a copy of inmec.github.io made in october of 2024.

## Limitations for use as template:
If you want to use this website as template do so, but consider the next limitations:
- The presentations fit inside the screens, if they both have 16:9 aspect ratio.
- The presentations work if each slide is in .png format.
- The presentations work if there are less than 20 slides.

## Change the presentations
To change the current presentations, replace the images in one of the next folder:
- presentation1/images
- presentation2/images
- presentation3/images
- presentation4/images
- presentation5/images
  
The slide number one it's called "out-01.png", the slide number it's called "out-02.png" and so on.

## From pdf to png
If you have a ".pdf" presentation convert it to ".png" images, for that propuse the next code works in Ubuntu terminals.

pdftoppm -r 500 -png "presentation.pdf" out

## Upload to github
There are tutorials made by github in the url "https://pages.github.com/". If you want to follow my steeps, i leave you the next procedure:

- Install git
- Open a git terminal
- Copy the website template to your pc using: https://github.com/InMec/website_template.git
- Replace the images with your presentation slides
- Create a Github account
- Create a repository named your_username.github.io
- Copy your website to your pc using: https://github.com/your_username/your_username.github.io
- Go inside the website folder using: cd your_username.github.io
- Open a folder manager and replace the images inside presentations1/images with your presentation slides.
- Run the next code in the git terminal: git add --all ; git commit -m "Initial commit" ; git push -u git@github.com:your_username/your_username.io.git main
- If you are in windows enter to your new github account
- If you are in linux open a new terminal and run: ssh-keygen -t ed25519 -C inmec@aol.com  
- Find the ssh-key generated inside the folder ~/.ssh, it has ".pub" format.
- Acces your github account and register the ssh-key
- Go back to the git terminal, cancel the runnig code with crtl+c, and run: ssh -T git@github.com  
- Add your email by running: git config --global user.email "your_email"  
- Add your name by running: git config --global user.email "your_name"  
- Run the next code in the git terminal: git add --all ; git commit -m "Initial commit" ; git push -u git@github.com:your_username/your_username.io.git main
