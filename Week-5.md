---
layout: default
---

## Week 5
23 July 2023

![An Arms Dealer in Cairo](/assets/images/header.jpg)
*Jean-Léon Gérôme,* An Arms Dealer in Cairo, *1869, oil on panel, 55.9 x 44.8 cm. Lusail Museum Collection. Photo: © Lusail Museum, Qatar Museums, 2022.*

### Task Summary
In my fifth - and final - week, I was tasked with using the Arduino microcontroller alongside RFID sensors to create a functioning prototype that could be used in the museum. This was to be done as a group project with Tooba, my fellow intern. I was also asked to present the AI tools I had found to the Lusail Team during our weekly meeting. 

Unfortunately, I was extremely ill for the majority of the week, so I was unable to do as much as I did during previous weeks. However, I did learn a lot in the short time I did have to work on my given tasks.

### The Presentation
Chronologically, the presentation was the first task I had to tackle. I am uncomfortable speaking in public - which is a step up from the outright, paralysing stage fright I used to have - so I had to mentally prepare myself for this presentation. I had finished the design the previous week, and the only thing that remained was the final touches.

![Presentation](/assets/images/w5.jpg)

This presentation was supposed to take place on Sunday, 23rd July. However, our meeting was pushed back a day, so it took place on Monday. In light of that, I utilized Sunday to refine the content on my slides and removed certain arbitrary tools that I didn't feel were relevant.

![Power Automate](/assets/images/w5_2.jpg)

On Monday, I did the presentation and answered the questions the Team had about AI, giving them my recommendations on how AI can be best utilized in its current state, given all the security risks and bad faith actors that may be developing tools using illegal data scraping.

Afterwards, I felt like the presentation went well enough but that I could have done better. However, that may not be objectively true as my presentation did impress certain members of the Team.

### The Hardware
I did not have an opportunity to work with the hardware until Thursday, due to my illness but I was given access to a multitude of sources by my supervisor, to give me an idea of where to start. I spent all of Sunday-Wednesday going through those sources and learning about the principles of human-centered design and the design thinking process. The principles themselves weren't new to me; a lot of the same principles are involved in entrepreneurship, which is a field I have been immersed in for the better part of three years. What was new, however, was the way they were applied in the museum setting.

I had already watched an explanation of the Lens at ACMI (an Australian museum with a focus on digital representations of art) from the makers of the Lens, but it was fascinating to read about the Pen at Cooper Hewitt. It showed a lot of the challenges that go into designing something so integral to the visitor experience. 

I also had access to the Tangible Media Group's projects, which showcased a massive range of the different ways in which technology can be used to display visuals, beyond just visuals on a screen.

Tooba and I brainstormed for a bit and came up with an idea to try to transform the audio guide QR code into a compatible form with the RFID scanner, so people could just scan "access" cards and be able to listen to the audio guide. We also played around with ideas of building temperature sensors that could be accessed from phones but all of these were vague ideas that we weren't even sure were possible.

In the end, we ended up working separately to make the Arduino microcontroller work with an LCD screen, the RFID scanner and then the RFID scanner and a couple of LEDs. The code was available online, so it was quite easy for me to work with the hardware itself, as I have experience working with Arduino. I ran into an issue with the LCD where the text would not display, which I was unable to troubleshoot. It seems like an issue in the code but I cannot be sure.

![RFID scanner code](/assets/images/w5_3.jpg)

The RFID scanner I managed to make work quite easily. There was an issue where it stopped scanning for a bit, but I got it working again after a few Google searches. I also got it to work with the LEDs, which was quite exciting.

### Challenges
The biggest challenge this week was my health. I was sick all week, which affected my ability to focus and be productive. At the time of writing this report, I am much better, for which I am grateful. 

Aside from that, I had a hard time with the RFID scanner, as I mentioned earlier. It scanned perfectly the first time but for an hour after the first test, the scanner would not detect any card. I thought the problem could have been with the scanner itself, as I had used my QM card to test it, which may have caused an issue. However, after extensive searching and troubleshooting, I realized it was a connection problem; the physical connections between the Arduino and the scanner were loose, which was causing the issue I was facing. I remedied that by holding the connections together manually during tests and that fixed the problem. Sometimes, it really is that simple :)

### Conclusion
Overall, I learned a lot about the process of integrating technology into the visitor experience. This is unique insight because as a visitor, I would never have the chance to learn what it takes and how much extensive research and testing it takes to create something that adds value to a guest's experience.

Over the course of this internship, that has been a recurring theme: gaining insights into areas that I normally wouldn't even consider. I am extremely grateful that I had the opportunity to experience everything I did. The last couple of months have been some of the most challenging; I have had to tackle projects that I don't know the first thing about. I have felt underqualified and overwhelmed. It definitely tested my resilience and my ability to learn under pressure. But I am glad that I pushed through and strove to learn as much as I could; I learned a lot more than I thought I would at the beginning, and I am excited to be able to apply this knowledge in my career. 

I also have to take a moment to thank my supervisor, Christophe, as none of this would have been possible without him. Christophe was extremely patient and supportive throughout this whole process, which gave me the confidence to continue. He gave clear instructions and provided feedback and guidance whenever I asked, and was instrumental to the success of this internship. All of the progress I made over the course of this internship has been in large part due to his actions. 

Thank you for everything. You were a fantastic mentor and I will always be grateful for the opportunity you gave me.

As this report comes to a close, alongside my internship, I have one final thing to say: thank you to everyone who played a part in bringing me here. Here's hoping for many more good times to come for us all.

[Previous: Week 4](./Week-4.html)

[Back](./)
