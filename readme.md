## Our session on Oct. 25th, 2022

This repo (short for repository) contains the activities for today's session.

#### At the end of the session all students will have a post with a text, an image and optionally an audio file on their own website. Furthermore, if time allows you have run with a patch on MAX 8, recorded a sequencer session and published it on your website.

### What should you do today?
- [ ] Create a GitHub account and an index.html file publishing some content on the web.
	- [ ] Set up your GitHub account
	- [ ] Create a repository with name for web publishing "username.github.io", create a file with name "index.html" with a simple message. Do not forget to Commit (save) your content (green button at the bottom of the page).
	- [ ] Check that your website with the simple message is visible on the web with the URL "username.github.io".
	- [ ] Think about a topic you want to write about and what materials you may be able to use. 
	- [ ] Create a scaffolding with outline for your website.
	- [ ] Discover HTML with [w3schools.com](https://www.w3schools.com/html/default.asp). Here you can also get the basic html code you need for your webpage, just copy and paste it from here to the index.html file on GitHub. ![w3schools.com](/media/w3schoolsEx.png)

	- [ ] You may use the w3school editor to create your site by copying and pasting various examples and modify them. 
		
### When you still have time ... some interesting stuff
- [ ] Add assets (images and audio files) to our website.
	- [ ] See how to show an image on your website [here](https://www.w3schools.com/tags/tag_img.asp)!
	- [ ] Download today's [GitHub](https://github.com/mibrs/GPC5L03) repo with some assets, uncompress it and then put it on the web. ![How to clone a repository from GitHub](/media/221025HowToCloneWithGitHub.png)

- [ ] Play a MAX patch and record it.
	- [ ] Install Audacity and Max 8 with Netsoft on the PC.
	- [ ] Launch MAX 8 with the sequencer patch and use Audacity to record a session (see video below for how to use Audacity).
  	- [ ] Export the recorded file to .mp3 with Audacity.
  	- [ ] Upload your audio .mp3 file to the repository of your website and publish the file. See [here](https://www.w3schools.com/html/html5_audio.asp) for the HTML code and modify it accordingly
  
### Something more to try out:
- [ ] Include a Youtube video to your webpage. Use the code snippets Youtube provide under the Share section below the video.

## Additional Resources

### This video explains how to make recordings of in-app or browser content on a Windows 10 machine.
<iframe width="560" height="315" src="https://www.youtube.com/embed/knL6uKBGyIg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Audacity settings for Windows 10 to record system sounds
This [blog post](https://mibrs.github.io/audio/web-design/2021/12/14/EMusic-Recording.html) shows the settings for Audacity, please choose them as shown in the red ellipses.

The code snippet below adds an audio player that allows you to play the mp3 file "220516Rec1.mp3" that has been saved in the folder "assets" inside your repository.

``` language=html
<div>
  <audio controls>
    <source src="/assets/220516Rec1.mp3" type="audio/mpeg">
  </audio>
</div>
```
### Get started with MAX 8
If you want to create your first patch with MAX (programs are called patches), [here](https://youtu.be/XQIWh4AnluI) is a Youtube video that gives you a first introduction.

### Another fun music source
[Ableton Learning Music](https://learningmusic.ableton.com) is another fun way to make music. Use Audacity as described above to record your own production.
