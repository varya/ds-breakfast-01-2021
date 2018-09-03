---

layout: ig

style: |

    #custom {
      background: black;
      padding-top: 0;
    }
    #custom h2 {
      color: yellow;
      margin-top: 70px;
    }

    .no-title h2 {
      display: none;
    }

    .code--size--m {
      font-size: 0.8em;
    }
    .slide .small {
      font-size: 50%;
    }
---

# How to use React, webpack and other buzzwords if there is no need  {#cover}

Varya Stepanova
{: .author }

<div class="title">
How to use

<span class="logos">
  <img src="pictures/react.png" class="logo react"/>,
  <img src="pictures/webpack.svg" class="logo webpack"/>
</span>
and other
<span class="buzz">buzzwords</span>
if there is no need
</div>

<!--
Cover image: http://www.adstasher.com/2013/06/k-y-jelly-love-machines-print-ads.html

I will share what strategy I used to learn new technologies in last 5 years.

-->

<style>

@import url('https://fonts.googleapis.com/css?family=Nunito');

#cover {
  text-align: left;
}

#cover:after {
  content: '';
  background-image:url('pictures/machine.jpg');
  background-size: cover;
  background-position: 0 0, center;
  opacity: 0.75;
  position: absolute;
  z-index: -1;
  top: 0;
  bottom: 0;
  right: 0;
  left: 0;
}

#cover:before {
  -webkit-filter: drop-shadow( -2px -2px 2px #000 );
  filter: drop-shadow( -2px -2px 2px #000 );
  text-align: left;
  width: 156px;
  height: 27px;
}

.author {
  font-size: 24px;
  margin-top: -5px;
  display: inline-block;
  position: absolute;
  right: 100px;
}

#cover h2 {
  display: none;
}

#cover .title {
  color: #FFF;
  font-size: 45px;
  font-family: 'Nunito', sans-serif;
  margin-top: 300px;
  line-height: 1.5em;
  text-align: center;
  -webkit-filter: drop-shadow( -2px -2px 2px #000 );
  filter: drop-shadow( -2px -2px 2px #000 );
}

#cover .title .logos {
  white-space: nowrap;
}

#cover .title .logo {
  height: 1.5em;
  margin-bottom: -20px;
}

#cover .title .buzz,
#cover .title .buzz * {
    -webkit-animation: cray 6s infinite steps(50);
          animation: cray 6s infinite steps(50);
  display: inline-block;
  font-size: 1.25em;
  color: pink;
}
@-webkit-keyframes cray {
  2% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
  }
  4% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  6% {
    font-weight: 100;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  8% {
    font-weight: 100;
    font-style: italic;
    text-decoration: line-through;
    text-transform: none;
  }
  10% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  12% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  14% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  16% {
    font-weight: 500;
    font-style: normal;
    text-decoration: none;
    text-transform: lowercase;
  }
  18% {
    font-weight: 700;
    font-style: italic;
    text-decoration: line-through;
    text-transform: none;
  }
  20% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  22% {
    font-weight: 200;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  24% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
    text-transform: lowercase;
  }
  26% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  28% {
    font-weight: 100;
    font-style: normal;
    text-decoration: line-through;
    text-transform: none;
  }
  30% {
    font-weight: 200;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  32% {
    font-weight: 400;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  34% {
    font-weight: 200;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  36% {
    font-weight: 500;
    font-style: italic;
    text-decoration: none;
  }
  38% {
    font-weight: 200;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  40% {
    font-weight: 100;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  42% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  44% {
    font-weight: 100;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  46% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
    text-transform: lowercase;
  }
  48% {
    font-weight: 700;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  50% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  52% {
    font-weight: 300;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  54% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  56% {
    font-weight: 400;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  58% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
  }
  60% {
    font-weight: 700;
    font-style: normal;
    text-decoration: none;
  }
  62% {
    font-weight: 200;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  64% {
    font-weight: 600;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  66% {
    font-weight: 400;
    font-style: normal;
    text-decoration: line-through;
    text-transform: none;
  }
  68% {
    font-weight: 300;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  70% {
    font-weight: 100;
    font-style: normal;
    text-decoration: line-through;
  }
  72% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  74% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
  }
  76% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  78% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  80% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  82% {
    font-weight: 100;
    font-style: normal;
    text-decoration: line-through;
    text-transform: none;
  }
  84% {
    font-weight: 200;
    font-style: normal;
    text-decoration: underline;
  }
  86% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
  }
  88% {
    font-weight: 600;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  90% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  92% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  94% {
    font-weight: 500;
    font-style: normal;
    text-decoration: line-through;
  }
  96% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
  }
  98% {
    font-weight: 100;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
}
@keyframes cray {
  2% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
  }
  4% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  6% {
    font-weight: 100;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  8% {
    font-weight: 100;
    font-style: italic;
    text-decoration: line-through;
    text-transform: none;
  }
  10% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  12% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  14% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  16% {
    font-weight: 500;
    font-style: normal;
    text-decoration: none;
    text-transform: lowercase;
  }
  18% {
    font-weight: 700;
    font-style: italic;
    text-decoration: line-through;
    text-transform: none;
  }
  20% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  22% {
    font-weight: 200;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  24% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
    text-transform: lowercase;
  }
  26% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  28% {
    font-weight: 100;
    font-style: normal;
    text-decoration: line-through;
    text-transform: none;
  }
  30% {
    font-weight: 200;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  32% {
    font-weight: 400;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  34% {
    font-weight: 200;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  36% {
    font-weight: 500;
    font-style: italic;
    text-decoration: none;
  }
  38% {
    font-weight: 200;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  40% {
    font-weight: 100;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  42% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  44% {
    font-weight: 100;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  46% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
    text-transform: lowercase;
  }
  48% {
    font-weight: 700;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  50% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  52% {
    font-weight: 300;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
  54% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  56% {
    font-weight: 400;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  58% {
    font-weight: 100;
    font-style: normal;
    text-decoration: none;
  }
  60% {
    font-weight: 700;
    font-style: normal;
    text-decoration: none;
  }
  62% {
    font-weight: 200;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  64% {
    font-weight: 600;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  66% {
    font-weight: 400;
    font-style: normal;
    text-decoration: line-through;
    text-transform: none;
  }
  68% {
    font-weight: 300;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  70% {
    font-weight: 100;
    font-style: normal;
    text-decoration: line-through;
  }
  72% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  74% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
  }
  76% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  78% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  80% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  82% {
    font-weight: 100;
    font-style: normal;
    text-decoration: line-through;
    text-transform: none;
  }
  84% {
    font-weight: 200;
    font-style: normal;
    text-decoration: underline;
  }
  86% {
    font-weight: 600;
    font-style: normal;
    text-decoration: none;
  }
  88% {
    font-weight: 600;
    font-style: normal;
    text-decoration: underline;
    text-transform: none;
  }
  90% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  92% {
    font-weight: 400;
    font-style: normal;
    text-decoration: none;
    text-transform: none;
  }
  94% {
    font-weight: 500;
    font-style: normal;
    text-decoration: line-through;
  }
  96% {
    font-weight: 300;
    font-style: normal;
    text-decoration: none;
  }
  98% {
    font-weight: 100;
    font-style: italic;
    text-decoration: none;
    text-transform: none;
  }
}


</style>

<!-- Picture credits: http://www.createmydreamlifestyle.com/index.php/2016/07/30/advantages-of-the-laptop-lifestyle/ -->


## Me
{: .no-title .about-me }

![](pictures/me.jpg){: .photo }

### Now
Design Systems Specialist<br/> at Intergalactico <sub class="small">Nordcloud Design Studio</sub>

### Before
TMG (Amsterdam, the Netherlands); Yandex&nbsp;(Moscow,&nbsp;Russia)

### Area of expertise
Components on the web: design systems, pattern libraries, SGDD, BEM. Techs: CSS, JavaScript, etc.

<!--

My name is Varya, I have experience in development working in small to large projects across the
world. The things I have been doing are about frontend and most of the project was around something which is
currently called "design systems". In previous years, this activity had many different names like "pattern libraries",
"styleguides", "component approach", "atomic design". But whatever the naming, it included developing encapsulated
interface components. A while ago it was BEM CSS and XSL for templating, then a few JavaScript frameworks whose names
history does not remember, a little bit of Angular and currently React. Of course, since it has always been something
modular, there were various building and documenting solutions.

-->

<style>
.about-me p {
  font-size: 80%;
}
.about-me .photo {
  float: left;
  width: 300px;
  margin-top: 1em;
  margin-bottom: 6em;
  margin-right: 1em;
  border-radius: 50%;
}
</style>


## How to study new?
{: .how .cover }

<!--

From time to time, I faced reality. In frontend, we have a new framework every two weeks :-) As an engineer, I need to
know the new things so that I could bring my expertise into the working project. On the other hand, we usually learn by
doing. But if the working project does not offer me possibility to learn these new frameworks, libraries and building
solutions, how can I gain knowledge? This is in fact chicken-egg problem. Trying to break this circle, people usually
come up with some pet projects. What could work as such a project?

-->

<style>
.how {
  background-image:url('pictures/chicken-egg.jpg');
  background-size: cover;
  background-position: 0 0, center;
  background-color: #FDED5B;
}
</style>


## Maybe a useful app?

![](pictures/todo.png)

<!--

I know that some people easily come up with a valuable idea what could be a pet project. But some don't, and they often
do something like ToDo application. BTW, I searched "ToDO" in Github, and it gave me nearly one hundred fifty thousand
repositories. So, ToDo app is a nice idea but I really wanted something useful.

-->

## Blog

* Overengineering
* Open source
* Hosted on GitHub
* Source in Markdown
* Generated HTML

<!--

With that in mind, 5 years ago I decided that I would make my own blog. I wanted a standalone solution so that nothing
would limit my experiments. That time, I decided that I am OK with a bit of overengineering. And the end of the day, I
am doing it not only for getting the things done but also for playing around with new technologies.
I decided that everything will be open, not only the code but the texts of my posts too. I host everything on GitHub,
and anyone can explore the codebase. I even got fixes for my broken grammar! The source of the posts is in Markdown, it
is GitHub friendly and can be even edited in its web interface. For hosting, I went with GitHub pages, and
because of that the blog is actually a static HTML website. All the pages are generated into plain HTML.

-->


## March 2013: ![](pictures/jekyll.png){: .jekyll }
{: .tech-stack--jekyll }

![](pictures/bem.png){: .bem }
![](pictures/gnu.png){: .gnu }
<span class="borschik">borschik</span>
<span class="bem-tools">bem-tools</span>
<span class="bem-core">bem-core</span>
<span class="csso">CSSO</span>

<!--

The first version was built in 2013. Initially I went with Jekyll because it is embedded into GitHub. I did not need any
building step which generates HTML, I just commited the Markdown sources and GitHub itself generated HTMLs for me
according to the config. This structure has already been gone but I still sometimes use Jekyll for some other things.
For example, this presentation is hosted on GitHub and built with Jekyll.

For the blog, I was interested to bring there more frontend technologies. I began with BEM CSS, and I built the bundle
with GNUmakefile. Then I tried borschik, bem-tools, used bem-core component library and optimized the CSS with CSSO.

-->

<style>

.tech-stack--jekyll h2 {
  margin-bottom: 1.5em;
  position: relative;
}

.tech-stack--jekyll .jekyll {
  height: 125px;
  margin-bottom: -30px;
  position: absolute;
  bottom: 0;
}

.tech-stack--jekyll .bem {
  height: 100px;
  margin-right: 50px;
}

.tech-stack--jekyll .gnu {
  height: 100px;
  margin-right: 50px;
}

/* latin-ext */
@font-face {
  font-family: 'Anton';
  font-style: normal;
  font-weight: 400;
  src: local('Anton Regular'), local('Anton-Regular'), url(https://fonts.gstatic.com/s/anton/v9/1Ptgg87LROyAm3K9-C8CSKlvPfE.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Anton';
  font-style: normal;
  font-weight: 400;
  src: local('Anton Regular'), local('Anton-Regular'), url(https://fonts.gstatic.com/s/anton/v9/1Ptgg87LROyAm3Kz-C8CSKlv.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

.tech-stack--jekyll .borschik {
  -webkit-box-sizing: content-box;
  -moz-box-sizing: content-box;
  box-sizing: content-box;
  border: none;
  font: normal 40px/normal "Anton", Helvetica, sans-serif;
  color: rgb(112, 112, 112);
  text-transform: uppercase;
  -o-text-overflow: clip;
  text-overflow: clip;
  letter-spacing: 4px;
  margin-right: 50px;

}

.tech-stack--jekyll .csso {
  font-family: Verdana;
  font-size: 50px;
  position: relative;
}
.tech-stack--jekyll .csso:after {
  position: absolute;
  top: 0;
  right: 0;
  content: 'O';
  color: red;
  line-height: 1.25em;
}

.tech-stack--jekyll .bem-core {
  font-family: 'CoreCircus', sans-serif;
  text-transform: uppercase;
  font-size: 40px;
  line-height: 1;
  color: #f98ca4;

  margin-right: 50px;
}

.tech-stack--jekyll .bem-tools {
  font-family: Menlo;
  font-size: 40px;
  white-space: nowrap;
  margin-right: 50px;
}


/*
 * Webfont: CoreCircus by S-Core
 * URL: http://www.myfonts.com/fonts/s-core/core-circus/regular/
 * Copyright: Copyright (c) 2013 by S-Core Co., Ltd.. All rights reserved.
 * Licensed pageviews: 10,000
*
 * Webfont: CoreCircus2DDot1 by S-Core
 * URL: http://www.myfonts.com/fonts/s-core/core-circus/dot1/
 * Copyright: Copyright (c) 2013 by S-Core Co., Ltd.. All rights reserved.
 * Licensed pageviews: 10,000
*/
@font-face {
  font-family: 'CoreCircus2DDot1';
  src: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_1_0.eot");
  src: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_1_0.eot?#iefix") format("embedded-opentype"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_1_0.woff2") format("woff2"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_1_0.woff") format("woff"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_1_0.ttf") format("truetype");
}
@font-face {
  font-family: 'CoreCircus';
  src: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_8_0.eot");
  src: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_8_0.eot?#iefix") format("embedded-opentype"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_8_0.woff2") format("woff2"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_8_0.woff") format("woff"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_8_0.ttf") format("truetype");
}
@font-face {
  font-family: 'CoreCircusPierrot4';
  src: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_13_0.eot");
  src: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_13_0.eot?#iefix") format("embedded-opentype"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_13_0.woff2") format("woff2"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_13_0.woff") format("woff"), url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/209981/333BF4_13_0.ttf") format("truetype");
}

</style>


## May 2014: <span class="docpad">DOCPAD</span>
{: .tech-stack--docpad }

![](pictures/grunt.svg){: .grunt }
![](pictures/gulp.svg){: .gulp }
<span class="styleguide">styleguide</span>
<span class="visual-tests">visual regression tests</span>

<!--

A year later I switch to Docpad for HTML generation and in parallel I experiemnted a lot with diffrent building
soltuions. It was all around BEM structure, even though it was pure CSS, the compoents were separated similar to how we
now do it in React. GNUmakefiles did not seem up to date solution and I switched first onto Grunt and later to Gulp.
Then I experimented not with technologies but with approaches. For example, I did styleguide-first approach when developing
the components for the interface. And since eveyrthing was componentized and documented, I could easily have visual
regression tests for the blocks.

-->

<style>

.tech-stack--docpad h2 {
  margin-bottom: 1.5em;
}

/* latin-ext */
@font-face {
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 600;
  src: local('Montserrat SemiBold'), local('Montserrat-SemiBold'), url(https://fonts.gstatic.com/s/montserrat/v12/JTURjIg1_i6t8kCHKm45_bZF3gfD_vx3rCubqg.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 600;
  src: local('Montserrat SemiBold'), local('Montserrat-SemiBold'), url(https://fonts.gstatic.com/s/montserrat/v12/JTURjIg1_i6t8kCHKm45_bZF3gnD_vx3rCs.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

.tech-stack--docpad .docpad {
  font-family: 'Montserrat', sans-serif;
  color: #3D3D3D;
}

.tech-stack--docpad .grunt {
  height: 125px;
  margin-right: 50px;
}

.tech-stack--docpad .gulp {
  height: 150px;
  margin-right: 50px;
}

.tech-stack--docpad .styleguide {
  font-family: 'CoreCircus', sans-serif;
  font-size: 50px;
}

/* latin-ext */
@font-face {
  font-family: 'Berkshire Swash';
  font-style: normal;
  font-weight: 400;
  src: local('Berkshire Swash Regular'), local('BerkshireSwash-Regular'), url(https://fonts.gstatic.com/s/berkshireswash/v6/ptRRTi-cavZOGqCvnNJDl5m5XmN_pM4zT305QaYc.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Berkshire Swash';
  font-style: normal;
  font-weight: 400;
  src: local('Berkshire Swash Regular'), local('BerkshireSwash-Regular'), url(https://fonts.gstatic.com/s/berkshireswash/v6/ptRRTi-cavZOGqCvnNJDl5m5XmN_qs4zT305QQ.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

.tech-stack--docpad .visual-tests {
  font-family: 'Berkshire Swash', cursive;
  font-size: 50px;
  white-space: nowrap;
  background: red;
  background: -webkit-linear-gradient(left, orange , yellow, green, cyan, blue, violet);
  background: -o-linear-gradient(right, orange, yellow, green, cyan, blue, violet);
  background: -moz-linear-gradient(right, orange, yellow, green, cyan, blue, violet);
  background: linear-gradient(to right, orange , yellow, green, cyan, blue, violet);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

## January 2017: ![](pictures/metalsmith.svg){: .metalsmith }
{: .tech-stack--metalsmith }


![](pictures/react.png){: .react } ![](pictures/webpack.png){: .webpack } ![](pictures/css-modules.svg){: .css-modules }

* A lot of plugins
* "Server" React + "client" React

<!--

About a year ago I really wanted to include React, webpack and some styling solution into the blog tech stack. But it is a very simple site and it does not
assume a lot of interactions on client. So, I was looking for a solution which helps me to use React when generating
static HTML. Ideally, I wanted also to have some little interactions. So, some components would be mounted on client.
And, of course, I wanted these two types of components to be from the same codebase.
I looked into some other generators which I don't remember and selected Metalsmith out of all. I like that it is very
much customizable. This is one of the reasons why reaclifying is possible: there is a plugin which allows to use React
components as templates.
It also gives a lot of control over the files which it processes, and I use it a lot.

-->

<style>
.tech-stack--metalsmith h2 {
  position: relative;
}

.tech-stack--metalsmith .metalsmith {
  height: 50px;
  position: absolute;
  bottom: 0;
  margin-left: 20px;
  margin-bottom: 5px;
}
.tech-stack--metalsmith .react {
  height: 60px;
  margin-right: 50px;
}
.tech-stack--metalsmith .webpack {
  height: 60px;
  margin-right: 50px;
}
.tech-stack--metalsmith .css-modules {
  height: 120px;
  margin-right: 50px;
  margin-bottom: -10px;
}
</style>


## File structure

    content/
      posts/
        my-awesome-post/
          index_<mark class="important">en</mark>.md
          index_<mark class="important">ru</mark>.md

[http://varya.me/<mark class="important">en</mark>/posts/my-awesome-post/](http://varya.me)<br/>
[http://varya.me/<mark class="important">ru</mark>/posts/my-awesome-post/](http://varya.me)

<!--

The full control over processing files helped a lot when dealing with multi-lingual structure of my blog. I write
posts in English and Russian, sometimes I translate, and sometimes posts are written in one language only. If the post
is available in both languages, I prefer to keep the sources together under the same directory. But when rendered into
the website, it looks much better if the language code works as prefix. Metalsmith gives me to manipulate all the
files in the stream, and change their location. Also, when generating HTML for a blog post, I can detect if there is
a translation to the opposite language or not. Then, I provide language switcher if possible.

-->


## Development flow

    npm run dev

* Runs development server
* Builds JavaScript and CSS bundles
* Generates HTML

<div/>

    npm run build

<!--
Frontend-wise, the building happens so that React components which work as templates are gathered together with
webpack. This makes possible to process imported CSS and images. JavaScript works to output the static HTML. Other results
of the build are CSS to apply to the page and another piece of JavaScript, which is needed for dynamic components. In
theory, since it is webpack, I can use all kinds of loaders and plugins. For example, it must be possible make it
very much optimized.
-->


## The Frontend
{: .frontend }

* React components for SSR
* React components for browser
* CSS modules for both
* ![](pictures/styled-components.png){: .styled-components .next }

<!--

So far, in current stack I use React components for server-side rendering and for browsers. In both, there are CSS
modules for styling. And I have started it just a couple days ago - there is styled-components for one component yet.
This is a funny story, I wanted to use styled-components long time and I am actually already using them at work. But in
the blog I has difficulties and I figured out that it is probably not possible due to some reasons. At the same time
preparing this talk forced me to fix some inaccurases in webpack configuration. And than I was like "what if I try
styled-components again?". And it worked! The only reason it sis not work previously was that I actually over-wrote the
CSS bundle because webpack configuration was wrong. So, maybe the idea for the next talk is "how to master the
technologies - just annonce a talk about them, then you have no choice but deliver".

-->

<style>
.frontend .styled-components {
  height: 250px;
}
</style>


## Pros & cons
{: .pros-cons }

### Happy

* Overengineering :-) Fancy new technologies
* Fast building process
* Not large codebase, open for experiments
* Ready for framework-of-the-week

### Sad

* Overengineering :-( Writing a blog and not writing for the blog
* Solution specific limits

<!--

It had been over a year since I switched the blog into Melatsmith with React, css-modules and Webpack. I am mostly
happy with this solution. Yes, it sometimes feels as overengineering because the website is so simple. But this was what
I wanted for playing around. Metalsmith is much faster than Jekyll or Docpad, so that I can stand the building process.
In general, a blog as a pet project is a very nice idea. It is yet simple, even with all the introduced technologies the
codebase it not large. It can be easily handled when I am making new experiments with some framework-of-the-week.
However, there are of course drawbacks. This overengineering results into writing the blog instead of writing for the
blog. And there are some soltuion specific limits. This styled-components story did not happen to me in my work project,
it was super easy to start using there but not in the blog.
Anyway, this is not the end. I think that I will refactor it again and again with other static generators. If you have
ideas, please share it with me.

-->

<style>
.pros-cons h2 {
  display: none;
}
</style>


## Thank you
{: .thanks }

Varya Stepanova, Intergalactico - Nordcloud Design Studio<br/>
[@varya_en](https://twitter.com/varya_en){: .twitter }; on the web: [varya.me](http://varya.me){: .web }

### Slides

### [varya.me/react-finland-2018](http://varya.me/react-finland-2018/)

<!--
Thank you very much! You can always reach me out in twitter, or in the afterparty.
-->

<style>
.thanks h3 {
  font-size: 28px;
  margin-bottom: 0.5em;
  margin-top: 1em;
  line-height: 1.25em;
}
.thanks .twitter
{
  text-decoration: none;
  color: currentColor;
  background: none;
  border-bottom: 0;
}
.thanks .twitter::before
{
  content: "";
  display: inline-block;
  width: 1.5em;
  height: 1.5em;
  background-image:url('pictures/twitter-logo.png');
  background-size: cover;
  margin-right: 0.5em;
  margin-bottom: -0.5em;
}
</style>
