## Bio

- **MSc. in Computer Engineering (2024 - Ankara University, Turkiye)**  
  My thesis is about problems I've discovered on using genetic programming for synthesizing Go programs out of unit tests and couple suggestions for dealing with them
  [Read full thesis in Turkish](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=weFMBHaUra8rsS5wi2bmHDKlIvi-IwlFkdPWTMwNi0k9Pt1C4PzNAFzxcjzHPgAW)
- **BSc. in Computer Engineering (2018 - Ankara University, Turkiye)**

## Contact

I am open to considering offers where the requirements match my projects fully or partially. Don't hesitate to send me an email using **your company account**. I will respond shortly after reviewing the company's public profile.

## Experienced Tools

- Go
  - [Gonfique](https://github.com/ufukty/gonfique) A code generator written in Go to produce Go code from YAML or JSON file
  - [ovpn-auth](https://github.com/ufukty/ovpn-auth) Easy to deploy OpenVPN authorization agent written in Go works offline
- Python (Matplotlib, NetworkX)
  - [Diffusion of Innovation](https://github.com/ufukty/diffusion-of-innovation) Written in Python with NetworkX and uses Matplotlib's pyplot
  - [reddit-galaxy](https://github.com/ufukty/reddit-galaxy) Written in Python with NetworkX and uses Matplotlib's pyplot. Processes the dataset with Scala
- Bash, Make
- JavaScript, TypeScript
  - [Gonfique Playground](https://github.com/ufukty/gonfique-playground) Written in TypeScript and compiled to JavaScript via Vite, built on Microsoft Monaco and loads a Go WASM binary.
  - [Dim](https://github.com/ufukty/dim) Visual Studio Code extension written in TypeScript
- Terraform, Packer (DigitalOcean)
  - [PR](https://github.com/hashicorp/terraform/pull/29127) for enabling Terraform users to encode and decode base32 strings
  - [PR](https://github.com/hashicorp/packer/pull/10093) for enabling Packer users to direct the provisioner to connect over private IP of droplet
- PHP
  - [Poor Man's Social Media](https://github.com/ufukty/poor-man-s-social-media) Written in PHP to process API requests happened as AJAX and to serve a simple frontend provides simple frontend interactivity through JavaScript
- C++
  - [TicTacToe AI with TUI](https://github.com/ufukty/TicTacToe-AI) Written in C++ and implements alpha-beta prunining
  - [ball-and-stick-man](https://github.com/ufukty/ball-and-stick-man) Written in C++ with GLUT

## Showcase

<style>
.ufukty-card {
    transition: all 160ms ease-out;
    border-radius: 12px; 

    &:hover {
        transform: scale(1.01);
        filter: brightness(1.1);
    }

    &.cast-shadow {
        box-shadow: 0 20px 40px #8884, 0 10px 10px #8884, 0 5px 4px -2px #8884;

        &:hover {
            box-shadow: 0 30px 50px #8884, 0 20px 24px #8884, 0 10px 12px #8884;
        }
    }
}
</style>

### [Gonfique Playground](https://github.com/ufukty/gonfique-playground)

<a href="https://github.com/ufukty/gonfique-playground"><img class="ufukty-card" src="https://github.com/ufukty/gonfique-playground/raw/main/assets/screenshot.png" attr="Screenshot of Gonfique Playground"></a>

Gonfique Playground brings Gonfique to browsers. It is a web app that works on Monaco editor and Golang WASM to give developers a extremely reactive environment where they can see the result of their changes in input file and Gonfique config in real time. The project is written in TypeScript and built with Vite to static files. Still works offline.

### [Gonfique](https://github.com/ufukty/gonfique)

<a href="https://github.com/ufukty/gonfique"><img class="ufukty-card cast-shadow" src="https://repository-images.githubusercontent.com/750442099/315b36fc-bada-4ba1-a2cf-d2001f4079be" alt="Gonfique logo"></a>

Offline and customizable YAML and JSON to Go for those who are not satisfied with the most popular <a href="https://mholt.github.io/json-to-go" target="_blank">Mholt's JSON-to-Go</a>. Pre-alpha of 2nd version brings new features like overriding resolved type expression, implementing struct iterators, providing option between struct and map representation for JSON/YAML objects, assigning parent refs on nodes; and improves existing features like auto generated type names by picking the shortest semantically correct name that doesn't collide with others, importing external packages for type replacement.

### [Dim](https://github.com/ufukty/dim)

<a href="https://github.com/ufukty/dim"><img class="ufukty-card cast-shadow" src="https://repository-images.githubusercontent.com/637051248/4f381212-7660-415d-abd6-e7d04454b04f" alt="Dim logo"></a>

A Visual Studio Code extension that reduces the opacity of matching statements and expressions to make the main logic pop. Intended for pushing the Go's error wrapping blocks and JS's logging lines to a little behind.

### [ovpn-auth](https://github.com/ufukty/ovpn-auth)

Basic authentication for OpenVPN server; supports time-based one-time-pads as well as password check and uses argon2 for hashes.

### [Reddit Galaxy (2021)](https://github.com/ufukty/reddit-galaxy)

Connection of subreddits represented with shared links between them. Linker end is orange, linked end is blue. Made with Apache Spark, Python, matplotlib

<a href="https://github.com/ufukty/reddit-galaxy"><img class="ufukty-card cast-shadow" src="https://github.com/ufukty/reddit-galaxy/raw/main/images/post-processed-1x-cg.jpg" alt="reddit galaxy"></a>

### [Diffusion of Innovation simulation (2020)](https://github.com/ufukty/diffusion-of-innovation)

Diffusion of a fake innovation is inspected in different community types while members promote from initial state to confirmation through 6 other states; s-curve on adoption and the role of higher-degree nodes are observed. Made with Python, matplotlib, NetworkX

<a href="https://github.com/ufukty/doi"><img class="ufukty-card cast-shadow" src="https://github.com/ufukty/doi/raw/main/images/scale_free_n_5000_a_098.gif" alt="diffusion of innovation project screen capture"></a>

### [ball-and-stick-man (2016)](https://github.com/ufukty/ball-and-stick-man)

Basic functionality, move camera, arms, touring, waving etc. Made with C++, OpenGL (GLUT)

<a href="https://github.com/ufukty/ball-and-stick-man"><img class="ufukty-card cast-shadow" src="https://github.com/ufukty/ball-and-stick-man/raw/main/img/footage.gif" alt="footage for ball-and-stick-man project"></a>

### [Poor Man's Social Media (2016,2024)](https://github.com/ufukty/poor-man-s-social-media)

<a href="https://github.com/ufukty/poor-man-s-social-media"><img class="ufukty-card cast-shadow" src="https://github.com/ufukty/poor-man-s-social-media/raw/main/assets/screencapture.gif" alt="screen capture of poor man's social media project"></a>
