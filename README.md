# Frontend Scaffolding

Frontend has become increasingly more complex over the years. At first, we were called web masters, web designers, and generalistic web developers. Nowadays, more responsibilities are attached to the client (in this case, the browser), and many dimensions exist now to be taken into consideration.

## Considerations before making a decision

### Team size and expertise

> How many people will be working on the project? What do they already know? Are we planning on hiring more?

This is important to know because of ramping up. Overall, senior engineers can handle new technologies well, as they come from the same root, but these professionals are scarce in the market. You might find more developers in more popular technologies, but you might be giving up cutting-edge tech because of that choice as well.

Also, your team should know how to apply the same technologies, coding practices, and style. That means, that the more level-aligned your team is, less time is spent in code reviews, pair programming, capacitation and workshops.

### Target audience

> Is your project aimed to internal users? What is their social background? What are their internet speed and bandwidth?

This information can be obtained from good UX research and is crucial for the business. It can set goals for dimensions such as browser compatibility, scalability, performance, and SEO. For example, if your product is used internally, you are probably not worried about how it would rank in search engines and which browser is used, as you can ensure they are using the same one.

In case your users are located in faraway locations and do not have access to fast internet, then there should be a focus on performance, optimizations, and bundling choices.

### Budget

> Can you contract supporting APIs, libraries and technologies to enhance this project?

Although it can be abstract information to apply when developing web applications, this can be important to keep in mind when choosing 3rd-party libraries or services. As the product grows, the project might pass to another tier, bringing costs it cannot pay. Also, this information can be used when coordinating with backend and cloud providers, as the amount of data passed through the wire matters. That, combined with other considerations, such as the target audience, might affect other dimensions such as SEO, where a good score and good practices will lead to more visibility and less money to be spent.

### Features of the product

> What will this web app do? Is it highly interactive or mostly static information?

This is one of the drivers of the technology choice. Some frameworks and libraries are optimized to do things over others. For example, if your site mostly consists of static content, like a blog, maybe Gatsby is a good choice, as it is easily integrated with most CMS platforms.

### Purpose of the product

> Is the goal of your website to get more people to know your company? Or is it a web app that provides specific tools, and subscription-based?

This can affect, for example, scalability and performance, how much computation you want the client or the server to handle. Also, how to optmize for marketing using SEO and coordinating better usability practices with designers.

### Server vs. Client

> How many responsibilities will each side have? How will each other communicate?

On a more technical side, communication between frontend and backend is important to define software architecture, how to know how data models will be received in the frontend, if they need to be serialized. Is it a REST API? What kind of endpoints to expect?

## Dimensions

These are the dimensions that will be covered in this guide. There will be different files, and the links will be here on the front page.

- Software architecture
- User experience and responsive design
- Framework and supporting libraries
- Build and bundling
- Styling
- Browser compatibility
- Scalability, performance, and SEO
- Accessibility
- Automation
- Server-side responsibilities
- Error handling
- Testing