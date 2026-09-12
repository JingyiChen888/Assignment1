# Assignment1-Why Are We Here?

We are moving toward a world in which almost anyone can generate code. A person without a strong technical background can now build a basic website, create an animation, or develop an interactive visual work. This does not mean that everyone has become a programmer, but it does mean that the technical barrier to creating digital work is becoming lower. As production becomes easier, the central question shifts from whether something can be made to whether it is meaningful or worth making. This is why I believe designers and artists still need to learn programming. Their goal is not to compete with AI in speed, but to understand the medium well enough to guide it, question its default results, and bring their own creative intentions and aesthetic judgement into the work.

## Aesthetic Output Is Not Artistic Intention

AI can produce images and interfaces that appear polished and visually convincing. Google's DeepDream experiments show how a neural network can generate surprising images by amplifying features learned from training data (Mordvintsev et al., 2015). However, producing an aesthetic result is not the same as having an artistic intention. The system can generate visual possibilities, but it does not have a personal reason or cultural position behind its choices. The person using it must still decide what the work should communicate and whether the result is meaningful.

## What the Machine Did Not Understand

When I worked as a product management intern, I used Claude to build an early prototype for a content management system (CMS). The goal was to turn product requirements into a working interface quickly, and at first Claude did this well. It generated pages, navigation, buttons, and basic interactions. However, when I tested one of the pages, the interface displayed two vertical scrollbars where I expected only one. I could see that something was wrong, but I did not know which part of the code was causing it.

I asked Claude several times to remove the extra scrollbar. Although the request seemed clear, its revisions either kept the problem or changed another part of the interface. I could describe the visible problem, but I could not specify the technical change that was needed. I eventually asked a front-end colleague for help. After inspecting the code, my colleague located and fixed the problem in about thirty seconds.

This contrast was important to me. From a product perspective, I could see that the two scrollbars made the interaction confusing. My design judgement allowed me to recognise the problem, but without enough programming knowledge, I could not trace its cause, change the system that produced it, or judge whether Claude was modifying the correct part of the code. The experience showed me that prompting and programming are not interchangeable skills. I do not need to write code faster than AI, but I need enough understanding to diagnose and control what it produces.

## Programming Beyond the Prompt

My experience with Claude made me realise that describing a desired result is different from specifying how a system should produce it. Designers who rely only on prompting remain dependent on the AI platform's interpretation of their words. They may recognise that an interface looks or feels wrong, but they cannot always identify which part of the generated system needs to change.

In *The Art of Code*, Beattie introduces a photographic artist who had previously been limited by what his existing tools allowed him to do. Learning programming enabled him to move beyond the interface and work more directly with the graphics engine (NDC Conferences, 2020). His experience also reflects Ihde's argument that technologies mediate how people perceive and experience the world (Ihde, 1990). A designer who only uses a tool can choose from its existing possibilities, while a designer who understands the system can begin to change those possibilities. For me, this is the value of learning programming: not necessarily writing every line myself, but understanding enough to make more intentional decisions about what the machine produces.


## Why I Am Here

AI may eventually become much better at understanding design intentions, and designers may need to write very little code by hand. However, this does not make programming knowledge irrelevant. The value of learning programming may shift from memorising syntax to understanding logic, structure, and system behaviour. Even if AI handles most of the production, designers still need to question its decisions, recognise when its defaults conflict with their intentions, and take responsibility for the final result. A more capable AI does not remove the need for judgement; it makes that judgement more important.

This is why I am here. My experience with the CMS prototype showed me that recognising a design problem is not always enough when I cannot locate it within the system. I want to learn programming so that I can move from describing what I want to specifying and shaping how it works. AI can expand what I create, but it should not determine the boundaries of my imagination.

## References

Ihde, D. (1990). *Technology and the lifeworld: From garden to earth*. Indiana University Press.
https://iupress.org/9780253114167/technology-and-the-lifeworld/

Mordvintsev, A., Olah, C., & Tyka, M. (2015, June 18). *Inceptionism: Going deeper into neural networks*. Google Research.
https://research.google/blog/inceptionism-going-deeper-into-neural-networks/

NDC Conferences. (2020, February 26). *The art of code—Dylan Beattie* [Video]. YouTube.
https://www.youtube.com/watch?v=6avJHaC3C2U