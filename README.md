# Milestone Project 1
## Website for my music production services

### Purpose of the site

I want to have a site that inspires confidence in my production services to a first time client. I intend to use funny audio samples to entertain and provoke interest. The snippets will be of a professional production standard, doubling as a kind of proof of ability. What I don't want is either a site that is dull or a site that is overly kooky. 

### Value of the site

The difficulty is: communicating the musical and organisational skills of an experienced music producer to a generation of clients who think of our work as an entirely technical profession. The site has value to a serious musical artist who is concerned that their musical vision is compromised by their financial means, technical knowhow and lack of trustworthy feedback. For that person, the combination of persuasive reasoning and snappy, responsive audio media would inspire the thought "Aha, this is exactly the combination of practical ability and creative orientation I am looking for." I would like people who are hesitant or unfamiliar with the lingo to feel welcome, by not using overly technical or cliquey language. 

Derek Sivers of CD Baby gives this advice: "find out who it is that you dont mind alienating, it will make your marketing strategy a lot clearer". In this case, I have very clear ideas of who I want to avoid: 

#### People who just want the cheapest service available.

I will not publish any price rates or mention any kind of special deals on the site. The overall design aesthetic should communicate quality, and do that in such a way that those people will instinctively think I'm too expensive for them. Its probably not going to deter every one of those people, but I like that as a starting point. This is a very common experience in our industry, that we waste a lot of time on communications with people who want it as close to free as possible. Usually the serious ones have no issue with our modest rates, and know that the reality of the process often means we go above and beyond what is remunerated. 

#### People who don't take their art seriously.

The artist/producer work process should be a meaningful collaboration that is focused on making something special. By making the sound snippets feature a wide variety of styles, I am hoping the sum of the difference communicates: "what this guy does is chameleonlike so its up to me to be the deciding creative force in this relationship". While sometimes the need to have income makes us slide on this issue a bit, it can really work against your reputation eventually. 

### Deployment procedure

Having struggled a bit with Bootstrap, I am relieved that it isn't strictly necessary for this project. I may end up using some features, but at the outset am leaning away from it. Kevin Powell's videos on Youtube have been a fantastic resource to learn CSS Flexbox and CSS Grid. 

#### Mobile first approach

At the time of writing, its a 5 page site. 

First thing (after setting fonts and colours) will be making my index.html page with a hamburger icon nav (see links below to where I learned a JS free way of doing it) and very basic footer. Footer has no social media links, since I don't use it very much. It will have some sort of a fun icon and maybe a (c) mainly for the visual accent. 

Copy and paste the nav and footer to all five pages.

Add background images and text areas in a block approach.

Margins, paddings, max-widths so that on a mobile view everything is nicely spaced.

#### Media queries

At a reasonable breakpoint, I will use media queries to organise the site into rows and columns. I intend to use the display:grid property as the heart of that. Each page will be a little bit different, but at the most complex I will still only have two columns for the main section. There may be a card at some point with a more complex nested grid structure, for the composition page. 

Since I have mocked up the desktop view on Figma, Im still not clear on what design elements will be best on a mobile. 

### Figma screenshots

Looking for the right image for the Rec/Mix page, but for now I am using this as a placeholder. Also, have yet to pick an accent colour out. I don't want a strictly black and white site, at least at this point... Fonts are also still being chosen. 

### Home page
![Home Page](readmeimg/home.png)
### Production page
![Production Page](readmeimg/prod.png)
### Recording/Mixing page
![Recording/Mixing Page](readmeimg/recmix.png)
### Composition page
![Composition Page](readmeimg/compose.png)
### Contact Page
![Contact Page](readmeimg/contact.png)


## Video resources

[KP Responsive design made easy](https://www.youtube.com/watch?v=bn-DQCifeQQ)

[KP Building a CSS Grid layout](https://www.youtube.com/watch?v=v5KzBPUEgGQ)



    

