# 100 Days Of Code - Log

### Day 0: January 3, 2017

**Today's Progress**: Start re-developing my personal website with [nextjs](https://github.com/zeit/next.js).

**Thoughts:** Really excited. I know something about the universal js used by next.js and I really want to know more about.  
Currently the experience is pretty good.
I'm developing kinda a static website for know, without the use of React.  
I'm also making some experiments with CSS animations.

**Link to work:**  
- [GitHub](https://github.com/lasalefamine/godev.space)
- [Demo (dev)](https://godevspace-cajaozvpyb.now.sh/)

---

### Day 1: January 4, 2017

**Today's Progress**: Progress with Nextjs. Updating to 2.0.0-beta and adding <Link> (next/prefetch) component for prefetching pages and activate client-side routing. Also some fixes.

**Thoughts:** Nice, only thing I have to struggle with is the scoped CSS. Some JSX and compilation errors to handle... That's a reason I prefer Polymer rather than React, but don't blame me please :D

**Link to work:**  
- [Revision](https://github.com/LasaleFamine/godev.space/commit/3a098d3adf99aede8e06fa19b40272bd20880e27)
- [Demo (dev)](https://godevspace-rkldvdtpcv.now.sh)

---

### Day 2: January 5, 2017

**Today's Progress**: Little break from my website and having fun with Web Speech APIs.

**Thoughts:** Incredibly easy to understand, I think I have to build something on top of it and a Raspberry PI :rocket:

**Link to work:**  
- [GitHub](https://github.com/LasaleFamine/learn-web-speech-api)
- Demo (nothing yet)

---

### Day 3: January 6, 2017

**Today's Progress**: Completed the Speech API prototype and put a demo online (thanks [now-static](https://zeit.co/blog/now-static)).  
Get back on my website with the last adjustment before the final deploy.

**Thoughts:** Is really easy to deploy live testing with ***now*** and I'm seriously thinking about get their premium plan.  
On other hand, I need to revisit the `next/prefetch` feature of **next.js**, maybe I need to write a real React component to better testing it.

**Link to work:**  
- [Revision (Web Speech API)](https://github.com/LasaleFamine/learn-web-speech-api/commit/71e6dd3b1410d48bbddb61249d25dd6be4bff89d)
- [Learn Web Speech API](https://learn-web-speech-api-tgcqfajvoq.now.sh)

- [Revision (godev.space)](https://github.com/LasaleFamine/godev.space/commit/0135e1863e080d1c22568bd7237c413b2df22972)
- [godev.space (Dev)](https://godev-space.now.sh)

---

### Day 4: January 7, 2017

**Today's Progress**: Today is the day of [vue.js](https://vuejs.org). I'm trying the [vue-cli] for building a simple dashboard of [now](https://zeit.co/now) deployments.  
I also fixed my little VPS to put live my godev.space website.

**Thoughts:** The first impression is good. I need a deeper knowledge of the framework before talking about pros and cons. I really need to setup testing.

**Link to work:**
- [GitHub](https://github.com/lasalefamine/now-dashboard)
- Demo (not yet)

---

### Day 5: January 8, 2017

**Today's Progress**: Realized I couldn't simply call the Zeit's Now APIs, I'm building a simple Hapi.js server for serving the web app in Vue.js and also to correctly call the Zeit's APIs.

**Thoughts:** I little disappointed that I can't call directly the Zeit's APIs but I understand their reasons. By the way it's good get back and practice with Hapi.js

**Link to work:**
- [Revision (now-dashboard)](https://github.com/LasaleFamine/now-dashboard/commit/6a43774ed1d6fc0859f56186e244cc6190fb24de)
- Demo (not yet)

- [GitHub (hapi-now-dashboard)](https://github.com/LasaleFamine/hapi-now-dashboard)

---

### Day 6: January 9, 2017

**Today's Progress**: Little stop from the ***now-dashboard*** (I think I will work on it later btw). I upgraded one of my Polymer component to a better Flexbox layout (really small changes), and also worked on a ***not public yet*** project of mine.

**Thoughts:** Want to practice too much with Flexbox. I'm starting loving it.

**Link to work:**
- [Revision (polymer-youtube-feed v0.3.0)](https://github.com/LasaleFamine/polymer-youtube-feed/commit/d065cf964d11b96575182fd77c08e04a87ad94f7)

---

### Day 7: January 10, 2017

**Today's Progress**: Back on the dashboard after put online my website [godev.space](https://godev.space).

**Thoughts:** I think I'm almost finishing with the very basic features: list of deployments and delete it (that's not implemented yet). The experience with Vue.js is really great, but I'm having trouble with unit testing.

**Link to work:**
- [Revision (now-dashboard)](https://github.com/LasaleFamine/now-dashboard/commit/aa558cdbfb15941b92c431ac9a015951f4341cf3)
- [Revision (hapi-now-dashboard)](https://github.com/LasaleFamine/hapi-now-dashboard/commit/cb3e8d5b175afe3a9e9ccaa7ded85295232e55e3)
- [Demo (with now!)](https://hapi-now-dashbaord-srkssrizpp.now.sh/)

---

### Day 8: January 11, 2017

**Today's Progress**: Progress on [now]() dashboard. Adding the delete command with some enhancements on UX and `DELETE` method on Hapi.js API

**Thoughts:** Vue.js is blazing fast also for learning. I think I will build more ***reactive interfaces*** with this great library.  
I'm also experimenting with different linting tools in both projects (UI and API).

**Link to work:**
- [Revision (now-dashboard)](https://github.com/LasaleFamine/now-dashboard/commit/8f9a6f1df025a836f876ec4229cdddfac0d48899)
- [Revision (hapi-now-dashboard)](https://github.com/LasaleFamine/hapi-now-dashboard/commit/3336c7946877679b2ef1249f6a0685e6452b5e51)
- Demo - need to wait 24 'cause too much deploys in the last 24H with ***now*** :sad:

---

### Day 9: January 12, 2017

**Today's Progress**: Another pause from the dashboard (almost complete) to start learning [Tensorflow](https://github.com/tensorflow/tensorflow). Just pulled the docker image and start practice with Python and Tensorflow.

**Thoughts:** My plan for 2017 is to go through deep/reinforcement learning and this is the starter point.

**Link to work:**
- [Starter guide](https://www.tensorflow.org/get_started/)

---

### Day 10: January 13, 2017

**Today's Progress**: Last mods to API's and UI for the dashboard and push it online with a better readme on repos.

**Thoughts:** The "cleaning". Better code, update linter and remove unused code. Also a better readme for the projects.

**Link to work:**
- [Revision (now-dashboard)](https://github.com/LasaleFamine/now-dashboard/commit/0fbde7f68dc53debf20b09c1f1d486fb87a3186b)
- [Revision (hapi-now-dashboard)](https://github.com/LasaleFamine/hapi-now-dashboard/commit/20bba2d299b9f0fcf4e8b5c5818ee431906792ce)
- [Demo](https://now-dashboard-acihatjstd.now.sh)

---

### Day 11: January 14, 2017

**Today's Progress**: Optimize performance and UX for the dashboard. Also first beta production deploy.

**Thoughts:** I'm going deeper with Vue.js and I want to go really more and more deeper!

**Link to work:**
- [Revision (now-dashboard)](https://github.com/LasaleFamine/now-dashboard/commits/master)
- [Revision (hapi-now-dashboard)](https://github.com/LasaleFamine/hapi-now-dashboard/commit/deaacebacb4bf6928022d1a06f4d423442a60340)
- [Demo (https://now-dashboard.now.sh)](https://now-dashboard.now.sh)

---

### Day 12-13: January 15-16, 2017

**Today's Progress**: Just fall into ***GO***. Practicing with the getting started a making some toys.

**Thoughts:** Reminds me the times of C at school :D I think could be also useful for my JavaScript knowledge to learn GO.

**Link to work:**
- [goquote](https://github.com/LasaleFamine/goquote)

---

### Day 14: January 17, 2017

**Today's Progress**: Progress with ***Go***. Building a basic Web API for an hypothetic TODO application.

**Thoughts:** I like the compilation time although my code is really small, it's about the process, the exact opposite to JavaScript btw :eggplant:

**Link to work:**
- [go-todo-api](https://github.com/LasaleFamine/go-todo-api)

---

### Day 15: January 18, 2017

**Today's Progress**: Working on the UI of the go-todo-api just to make everything work as expected in a to-do application. Vanilla js and [clab-ui-components](https://github.com/contactlab/contactlab-ui-components)

**Thoughts:** Today it's just about testing something which I contributed and it's awesome to see our web-components written in **Polymer** are working with charm in a ***vanilla js website-like***.

**Link to work:**
- [Revision (go-todo-api)](https://github.com/LasaleFamine/go-todo-api/commit/21794d5ca0b219296e94991a5c20703bbca38a6c)

---

### Day 16-17: January 19-20, 2017

**Today's Progress**: Progress with ***Go*** routing and better UI. Almost done with this experiment.

**Thoughts:** I'm learning a lot about ***Go*** and I'm excited to learn more.

**Link to work:**
- [Revision (go-todo-api)](https://github.com/LasaleFamine/go-todo-api/commit/8343799a5667b98b020bac155265b8014df1f8cd)

---

### Day 18: January 21, 2017

**Today's Progress**: Pause from ***Go*** after ended a little (but working) UI for the to-do application, with a live demo. I'm coming back to **Tensorflow** and ***Machine Learning*** :robot:

**Thoughts:** Come back to Python is every time a pleasure, a big one if is for Machine Learning. I started with some overwhelming tutorials, but now I think I found my way.

**Link to work:**
- [(go-todo-api)](https://github.com/lasalefamine/go-todo-api)
- [(learn-machine-learning)](https://github.com/lasalefamine/learn-machine-learning)

---

### January 22 - Pause

---

### Day 19-20: January 23-24, 2017

**Today's Progress**: Just a little deviation to my JavaScript crafting and releasing a new ***nodejs*** module for `runnable exports`. After that I'm working on a ***codelabs*** (by Google): **TensorFlow for Poets**

**Thoughts:** I forked the idea of the module from another great module, but I revisited to ES2015 the entire code and also wrote some tests. Used Coveralls for the first time!  
The ***codelab*** btw seems really interesting.

**Link to work:**
- [(runnable-exports)](https://github.com/lasalefamine/runnable-exports)
- [(tensorflow-for-poets)]()

---

### Day 21: January 25, 2017

**Today's Progress**: Since I can't handle (just for now) a great ***TensorFlow*** training, I switched to a project of mine that is not public yet (but will be soon). But of course I can say is a Polymer Progressive Web App :rocket:

**Thoughts:** I need to put a VM or use Docker with my Windows machine for TensorFlow 'cause with the MBP I really can't handle this.

**Link to work:**
- [Secret project (not yet...)]

---

### Day 22-23: January 26-27, 2017

**Today's Progress**: The 22th just worked on my secret project written in Polymer. Today stop from the project and start with a new challenge: [FreeRadius]() and networking.

**Thoughts:** This new argument will be a real pain in the ass but I want and I need to know much more about networking and Radius management. But for today is just about set up the enviroment for development and learning.

**Link to work:**
- [Nothing yet]

---

### January 28 - Pause

---


### Day 24: January 29, 2017

**Today's Progress**: Trying to figure out how to work with FreeRadius and MySQL with `docker` and `docker-compose`.

**Thoughts:** Networking is not my field, but I like to learn about what I don't know at all. :D

**Link to work:**
- [Nothing yet]
