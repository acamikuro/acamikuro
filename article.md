What I've learnt in 1 month of programming

### 1. **Starting from Scratch**
Less than a month ago, I was completely clueless about coding languages, programming, or anything related to coding. I mean, I had a vague notion that it was a profession, and lots of people did it, but for me, it was like, "Developers? How do they even survive? Where do they work? Do they exist for real?" LOL, I was pretty much in the dark.

Then, I attended my first tech event called **Frontin Sampa**, and something clicked in my head. I decided right then and there: "I'm going to dive into programming and **switch up my career**." I even shared more details about this journey in this [article](https://dev.to/acamikuro/-uma-produtora-de-tv-no-mundo-dev-44p3)(it's in Portuguese, by the way).


So, with zero prior knowledge, I embarked on my programming journey armed with a [**basic roadmap**]([https://trilha.info/roadmap/frontend](https://trilha.info/roadmap/frontend)) that proved to be incredibly helpful for a newbie like me. The best part? It had loads of **free resources** to pick up along the way!

[roadmap image](https://imgur.com/a/ZpAqEjp)

In addition to learning the basics of **front-end** programming, I dedicated myself to understanding the concept of **open source**, which was one of the talks I watched in the tech event and was completely amazed by.

Another crucial part of my journey was becoming an active member of a tech community. Today, I'm proudly part of [He4rt Developers](https://discord.gg/he4rt), a thriving community. Inside, we have insightful discussions on important topics, **collaborative projects**, weekly meetings, and beginner-friendly free projects to work on.

But wait, there's more! From the second week of my studies, I started getting some guidance and exploring more complex topics (well, for those in the know, it's probably not that complex, right?). I had a great grasp of the front-end, but when I ventured into the **back-end**... oh boy, it was like an avalanche of code.

Moreover, what has encouraged me to study every day is the ["100 Days of Code"](https://www.100diasdecodigo.dev/#comoParticipar) challenge, created by the He4rt Devs community. This challenge encouraged me to share what I learned and track my progress every day.

In my mentoring sessions, I dived into concepts like HTTP, Linux, the difference between Git and GitHub, and got a brief introduction to database modeling. It might seem like a lot to cover in such a short period, but I managed to grasp the basics, and now I'm going to break it all down for you!
### 2. Concepts I've Mastered So Far

#### 1. Open source
My journey began with exploring the concept of "**open source**," which is a **software licensing model** that allows anyone to access the source code. In simpler terms, it means that anyone can tinker with, modify, contribute to, and distribute the code according to the specific terms of its license.

At that point, I thought, "Alright, I get the concept, but show me some examples!" So, I continued my research and learned more about the open-source Linux operating system. Don't worry; I'll talk about **Linux** in a bit. Another example of open source is the participation of companies, even tech giants, in open source projects and their use of **open source software** in their daily operations.

Working with open source has its perks, such as transparency, collaboration, and the creation of vibrant communities that work together on projects openly.

#### 2. The Basics: HTML, CSS and JS
Next up on my journey was diving into the basics of programming, starting with the iconic "hello world." Thanks to that roadmap I mentioned earlier, I knew exactly where to begin. I kicked off my HTML studies with a comprehensive online course, where I learned the coding terminology, the actual code, and how to use it properly to command the desired outcomes. HTML is what lays the foundation of a website. It uses "tags" to define elements like headings, paragraphs, and images, telling the browser how to display them on the page.

Then, I moved on to CSS, which turned out to be one of my favorite parts of the journey. Having the power to change every visual aspect of a website is just mind-blowing, and with each lesson, as I learned something new, I'd experiment to see if it made sense and, of course, if it worked (and it totally does, by the way). CSS is responsible for the look and style of HTML content. With it, you can tweak colors, font sizes, spacing, and even the position of elements on the page, making everything look stunning and organized.

Finally, JavaScript entered the scene, and I thought I'd seen cool stuff before, but this was on another level. JavaScript is what brings a website to life, making it interactive. You can create buttons that do something when clicked, update parts of the page without reloading everything, and so much more.

#### 3. Documenting My Journey
While I was diving into HTML, I also started online mentoring sessions on other subjects. During these sessions, I learned the importance of taking notes in a bullet-point format as I went along, making it super easy to reference later. I also learned how to create notes in markdown and realized why we see "md" at the end of files like "README.md." Plus, most of these mentorships were conducted in English, which helped me improve my technical vocabulary and conversational skills.
#### 4. Git and GitHub
In one of my mentoring sessions, we dove into the differences between Git and GitHub, along with the jargon associated with both:

```
* Git
	* Tool for versioning your codebase
	* Terminology:
		* Repository (project) - getting-started
			* Branches (environments inside a project)
				* Commits - (changes into the codebase)
* GitHub
	* (Cloud Environment) Host the repository
	* Issues - Place to discuss bug, glitch, improvements, fixes, ideas or w/e
	* Pull Request - Submit changes into the codebase (in different branch/fork)
* Setup my GitHub account
	* create a READ.md 
	* add commits 
```

**"Git"** is a critical tool for version control that enables developers to collaborate effectively on projects, while **"GitHub"** is the platform that hosts Git repositories and simplifies teamwork. Learning these tools gave me the ability to contribute to open source projects and share my code with the community.


#### 5. Linux Basics
The next topic in my mentoring journey was the Linux operating system, which is open source, meaning the source code is freely accessible for anyone to view, modify, and distribute. With this openness, a large community of developers and enthusiasts can contribute to its development and create their own versions based on the Linux kernel. Some popular Linux distributions include Ubuntu, Debian, Red Hat, and CentOS.

Just like with other mentorships, my notes looked something like this:

```
* Linux 101
	* Distributions
		* Kernel, Package Manager, Drivers, Tools/Tooling and Shell
		* Graphic Environment: 
			* Gnome (Ubuntu)
			* Kubuntu (KDE)
			* OS X (Plasma)
			* Link to [UnixPorn] (https://www.reddit.com/r/unixporn)
```

After getting a grasp of the theory, it was time to get hands-on. Using the command "**cat .bashrc,**" I could view all the existing commands. So, I decided to create one more command by accessing "**nano .bashrc**" and voila!
#### 6. HTTP Protocol
To wrap up the concepts I've covered, let me explain **HTTP**, which stands for Hypertext Transfer Protocol. It's the glue that **connects** the client and server in web interactions. The client could be your web browser, a mobile app, or anything that uses HTTP. The server, on the other hand, is where a request is sent, and a response is received.

Whenever we request data or services from a server, it can respond with status codes represented by numbers. You've probably heard of "**404**" which means "**not found**", but there are others like "**201 - Created**" and "**500 - Internal Server Error.**" During one of my mentoring sessions, I was given a website that showcased all these status codes with [kitten memes](https://http.cat/) and a brief description. It was fantastic and helped me grasp each one of those statuses better.

[201 - Created cat meme](https://imgur.com/a/OO58ioL) 

HTTP also uses **verbs** like **"GET"** to get information and **"POST"** to send or publish data to a server. Also, it can work with JSON, a document model usually used  for analyzing and transforming data. This makes HTTP a fundamental protocol for all our online activities.
### 3. Conclusion
After one month of daily coding, exploring concepts, and engaging in activities, I can confidently say that I've transformed from someone who knew absolutely nothing about this field to someone with a solid foundation. And you know what? I'm thrilled to share all of it with you in this article.

One of my next steps is definitely to hone my practical and technical skills (you know, more coding), and who knows, maybe even apply for a job in this field. The career transition is already underway, and I couldn't be more excited!
