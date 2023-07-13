---
layout: default
---

## Week 3
9 July 2023

![Girl with a Pomegranate](/assets/images/img.jpg)
*Image credit: William Bouguereau,* Girl with a Pomegranate, *1875, oil on canvas, 59 x 44.5 cm. Lusail Museum Collection. Photo: © Lusail Museum, Qatar Museums, 2022.*

### Task Summary

In my third week, I was tasked with creating a prototype exhibition catalogue for Lusail Museum's *Tales of a Connected World* collection. I was asked to use Quire, a multiplatform publishing tool released in 2022. Quire provided the infrastructure of the catalogue, which had to be edited using a text editor; the content was obtained from Lusail Museum's website.

The final version can be found [here](https://amamah-qm.github.io/exhibition-catalogue/). However, due to reasons unknown, the website did not deploy with any of the styling that is available on the local server. As such, I've included some screenshots below, and through the rest of this post, of what the catalogue looks like locally.

![Front Page](/assets/images/frontpg.jpg)

![Contents Page](/assets/images/contents.jpg)

![Catalogue](/assets/images/cat.jpg)

I started the task on day 3; the first day was spent exploring AI tools (details below), and the second day was devoted to a tour of the 3-2-1 Qatar Olympics and Sports Museum, to explore different forms of multimedia and the varied ways in which the public can interact with them. 

### AI Exploration

I looked into transcription and summary tools for meetings, as those would be the easiest to adopt and provide utility to the whole team. The tools I looked into are Microsoft Teams' internal auto-transcription, tl;dv and Airgram. 

Tl;dv has been quite popular recently and I thought it might be a good fit. The reviews painted a favorable picture and it had a correspondingly high rating. However, it doesn't provide integration with Teams, making it an unviable option.

The next program, Airgram, looked much more promising, as it had the same rating as tl;dv. Airgram provides more features for a lower cost and has integration with MS Teams. From the reviews, the integration is almost seamless, which I will test myself in the coming week.

Unfortunately, I could not test Teams' internal software as I do not have access to it.

I will also be looking into other AI software in the coming week, trying to explore what functions AI can reliably perform, while also offering intuitive user experiences.

### Tour of 3-2-1 Qatar Olympic and Sports Museum

The tour of the Sports Museum allowed me the opportunity to look into creative and interactive forms of multimedia, beyond touch screens and narrative pods.

We watched a movie on the history of the Olympics that was displayed using three screens to give it a sense of depth. We used vertical interactive screens that I personally believe might be more effective than horizontal versions. We ventured into the activation zone and learned how the museum incorporates RFID technology into the available activities, which not only streamlines the registration process but also makes it more fun.

All of this gave me a fresh perspective on how technology can be implemented to improve and elevate the user experience in a museum setting, which in turn will also provide inspiration when I think of methods to implement technology in other settings.

### Exhibition Catalogue

The exhibition catalogue was a very unique task, unlike anything I've ever done before. Generally, whenever I have been asked to create something like a magazine, I've had to use software like Canva, which utilizes drag-and-drop features to help you arrange elements on the page (alongside designing and editing features); a very front-end-sided method of design. Using Quire was the polar opposite: everything had to be designed at the back end. 

This was my first attempt at using Visual Studio Code as a text editor; my go-to used to be Notepad, as it was what I was used to and I liked the challenge. Additionally, I learned some Windows Powershell commands to be able to create, preview and build the catalogue using Quire. This was also the first time I used Git Bash and GitHub Desktop, to push the repository to GitHub and publish it using GitHub Pages.

In the end, I was successfully able to create the catalogue, including replacing every image and changing the color scheme to match Lusail Museum's brand guidelines. Unfortunately, as mentioned previously, the website does not display any of the styles implemented in the code and presents as a basic HTML webpage. There is certainly a workaround to that but I have not found it yet.

Here are additional images from the local version:

![Catalogue 2](/assets/images/cat2.jpg)

![Catalogue 2 Table](/assets/images/cat2table.jpg)

![Essay](/assets/images/essay.jpg)

### Challenges

This task was frankly much easier than the audio guide. There is a strong possibility that this is not an objective viewpoint, as the ease may just be a result of my slowly increasing familiarity with coding, however, that is what my experience was. I found the process fairly intuitive, and therefore, I did not run into nearly as many issues as last week. The issues I did face were these:

- The figures.yaml file was difficult to update, as it would not accept a new image if you changed related the ID used in the document. So, if I changed the image ID from "lange" to "jlg" (Jean L. Gerome), and changed the image source, and then changed the ID in the .md file respectively, the image would not change. This took a while to get around.
- The "contributor" information did not change on every page after editing the publication.yaml file. I still do not know why this happened but after changing it initially, the information did not update. I spent a long time trying to fix it but it showed no change.
- At one point, the website stopped loading. Rather than spending more time trying to troubleshoot issues that I did not have the skill to fully understand, I decided to wipe the slate clean and start fresh. So I deleted the whole folder and restarted the build process.

The second time around, it went a lot smoother. I refreshed the preview after every change or two and that allowed me to discover that one of the image types in the default files is a very specific type of input and cannot be replaced by any other image. This is probably what broke the first attempt but I had made so many changes that I would never have realized it. Once I discovered that, I changed the input type and faced no more image-related issues

- The final issue was figuring out how to change the colors used. This folder has 31 .scss files and even after going through them all, I could not find where the color dependencies were located. My assumption was that elements like "$content-background-color" were coming from a file that declared what those values were. I did not find this file.

My workaround to this issue was an ill-advised one: I edited the color properties in the colors.scss file. This file stated color variables like "$black", "$red", "$off-black-semi-transparent", etc. and had the appropriate hex code assigned to each variable. I edited the hex code to the Lusail Museum's brand colors and left the variable names as they were. This proved effective and I was able to edit the colors as I wanted. 

Incidentally, this is the same fix I implemented for the images; wherein I changed the source but left the IDs as they were. It was equally effective in that case. I do believe that this approach is ill-advised as I need to learn to be able to customize the variables to fit my needs, but for the short-term, I favored effectuality over diligence.
 
### Conclusion

Overall, my third week was highly productive and enlightening. With every task I attempt at this internship, my confidence in using unknown software grows. This is invaluable to me as not only am I getting the opportunity to use software that is widely used today, but I will also be less hesitant when I have to adapt to new software later in my career. 

With every challenge that I face and overcome, I'm growing exponentially in terms of skill. I am grateful for this opportunity and I am excited to see where I will be, skill-wise, at the time of the next weekly report.

  
[Previous: Week 2](./another-page-2.html)

[Back](./)
