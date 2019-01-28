# Info

## List if ideas

1. Using Styleguidist and Storybook for non React projects (generate stories)
1. Visual tests based on styleguides (incl automated visual tests)
1. Gatsby website for design systems
1. Inserting React components into markdown in Gatsby
1. Greating interactive documentation (insert React component)
1. Welcome to edit the markdown source
1. Gather all the contributor names from GitHub
1. Use different sources (e.g. Wordpress) to make blogging culture
1. Extract md of dependent packages and turn into Gatsby pages
1. Build charts based on gathered knowledge
1. Crawling the repositories to calculate the usage of components.
1. Interactive changelog? Based on static data from GitHub. Idea - improve GitHub flow.
1. Design systems are verry new concept, so sharp it to your own project. Use design thinking and user centred design
(we can speak about it)

## Random thoughts
### Using high-level tools
Design systems are often presented as high-level component libraries. Usage of modern technologies gives a lot of benefits. At the same time, in real projects there can be different reasons for legacy. For example, some companies stay with pure CSS/HTML libraries. How can they take advantage of the fancy approaches from the conferences?

You don't have to change the way how you write your docs. For example, your docs are as comments in code. Styleguidist or Storybook cannot read them. But you can write a script to generate suitable styleguide docs automatically.

Don't forget to Reactify your code.

Consider this automation as a small step towards new technologies. One day they will come to your project as well. By that time you already have some set up for the tools.

### Visual regression tests
I have a lot of experience with custom set ups. It takes time to maintain. It's always better to re-use the community work. Styleguide tools often provide plugins for visual regression tests. They are easy to install. If there is bug, it will be fixed faster than in your own project.

Combining this idea with generating stories, you can take advantage of the plugins even for non-React projects. This is not only about visual tests. If we generalize the idea, we can think about using React ecosystem for non-React projects.

### Gatsby website for design systems
Design system needs a website as "single point of truth". Styleguide is not such a website but just a part of it. Design system is not only a library, also a visual language. On the most high level, it is processes and community work. Everything has to be documented. So, make a website.

At the same time, it's good to automate as much as possible. So, it dictates the technical solution behind the website. My experience was with Gatsby. It was a lot of plugins, and you can write your own plugins (quite easy). I can show you some things to implement with it.

### Inserting React components into markdown in Gatsby
Example of Gatsby flexibility - you can insert React compnents into markdown, and they will be rendered. This way you can get React components from your library and describe them in a very flexible way on pages. A designer can write a text an illustrate it with the component. If you have "Reactified components", you can use it as well. It will also help the mind shift from HTML snippets to React tags.

Besides, you can make custom components. They are not from your library but whatever else. Here only your fantacy can limit you. This way you create interactive documentation. Here are some examples from my experience:
* Pattern Journey
* Changelog (but later we did it differently)
* Cartoon about flow

### Welcome to edit the markdown source
Involve the community into the Design System project. Wokr with emotional ownership. Since it's markdown and we store it on GitHub, we can welcome people to edit. This speeds up the process of making docs actual.

### Gather all the contributor names from GitHub
To continue, gather names of contributors and show them as the authors of the page. This is like a prize. Also, it helps people to communicate. They can see whom to ask about specific things.

### Use different sources (e.g. Wordpress) to make blogging culture
Markdown is the easiest to build but quite a hardcore way for many. But with Gatsby you can have different  sources. For example, you can set up Wordpress as a CMS. Designers write posts, information is open. Also you can import from Medium, or from anywhere via RSS.