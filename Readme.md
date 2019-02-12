# Info

## List of ideas

1. Using Styleguidist and Storybook for non React projects (generate stories)
1. Visual tests based on styleguides (incl automated visual tests)
1. Gatsby website for design systems
1. Inserting React components into markdown in Gatsby
1. Greating interactive documentation (insert React component)
1. Welcome to edit the markdown source
1. Gather all the contributor names from GitHub
1. Use different sources (e.g. Wordpress) to make blogging culture
1. Extract md of dependent packages and turn into Gatsby pages
1. Interactive changelog? Based on static data from GitHub. Idea - improve GitHub flow.
1. Crawling the repositories to calculate the usage of components
1. Build charts based on gathered knowledge
1. Design systems are very new concept, so sharp it to your own project. Use design thinking and user centred design
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

### Extract md of dependent packages and turn into Gatsby pages
The design system website as "single point of truth". Design system itself is single point of truth, so should be the website about it. All the information has to be gathered together, it also smooths the learning curve. Technically you can install the libraries packages as dependencies and import their markdown docs into website pages. TODO: refer to remark plugin for importing.

### Interactive changelog?
Similarly, we can get changelogs of the libraries. In GitHub they are stored as static pieces of text which is not super convinient when our fellow developers want to upgrade through many versions. We can improve GitHub flow and based on the extracted data make some kind of interactive changelog. This again smooths the learning curve and makes things easier for the people (one of the most important things in design systes, because it's a service!).

### Crawling the repositories to calculate the usage of components
This is more about measuring the impact of design systems, which is another huge topic. BTW, I am very much in it right now and if you would like to have a chat about it, please welcome to speak after the talk or in social networks. But again, from automation perrspective, if all the projects are in some repositories, let's say on GitHub Enterprise, wee can crawl repos and calculate the usage of components. Works for React components and for re-use of CSS classes. Similarly, we analyse dependencies in `package.json` at the projects and so we can learn the versions used.

### Build charts based on gathered knowledge
Most metrics cannot show much on their own but are more valuable in dynamics. As design system is usually not a solid product but constansly evolving thing (I would even say it's a process), we would like to "measure" that we are doing better not worse. For a human being, it's much more readable as a chart of graph. So, we can store gathered information and represent it on the weebsite as a chart component. TODO: Give examples.

### Design systems are very new concept, so shape it to your own project. Use design thinking and user centred design
As I mentioned, design system is a service and when providing tooling around it, you should consider your fellow developers and the users. Service design offers methods to develop new ideas and sharp the services for the users. Like, user-centred design etc. The ideas presenetd above were very much developed based on propoper user research which I made with my colleagues on existing design system. Usign similar methods, you can develop your own ideas or combine with the presented and shape your design system up to the needs of your company and projects.