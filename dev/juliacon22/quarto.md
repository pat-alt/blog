
## Abstract 

Scientific publications come in many forms: Markdown, HTML, PDF, ePub and more. Wouldn't it be nice to have a tool that can produce all of these different output formats from the same input? With [Quarto](https://quarto.org/) scientific publishing always starts from the same place: a plain Markdown document blended with essentially any programming language of your choice and a YAML header defining your output. I would like to demonstrate its potential value for the Julia community.

## Description

#### Problem: so many output formats 😫

Does your work involve research, writing and publishing? Do you code in Julia and perhaps even other programming languages from time to time? If so, then chances are that you often find yourself bouncing back and forth between different open-source text editors, IDEs and platforms depending on your current needs. Using a diverse set of tools is reasonable, because there typically is no single perfect approach that solves all our problems. But as much as the great variety of free tools deserves being celebrated, all of this bouncing back and forth can be really tiring. 

#### Solution: Quarto 🎁

What if there was a single tool, an engine that can turn your hard work into all kinds of different outputs? I mean literally any output you can think of: Markdown, HTML, PDF, LateX, ePub, entire websites, presentations, MS Word, OpenOffice, … the list goes on. All of that starting from the same place: a plain Markdown document blended with essentially any programming language of your choice and a YAML header defining your output format. This tool now exists and it goes by the name [Quarto](https://quarto.org/).

#### Quarto and Julia 🤩

In this experience talk I would like to provide a brief introduction to Quarto and its interaction with Julia. I would like to talk about my setup, workflow and the interplay between Quarto and `Documenter.jl`. As an example, I will show how I've used Quarto during the development of my new Julia package: [CounterfactualExplanations.jl](https://www.paltmeyer.com/CounterfactualExplanations.jl/stable/).  

I'd also like to demonstrate how and why Quarto could be leveraged to turn the JuliaCon Proceedings Journal into one of the most innovative journals out there. Taking inspiration from the likes of [Distill](https://distill.pub/) and the [RStudio AI Blog](https://blogs.rstudio.com/ai/), a digital version of the journal could include interactive elements and versioning, among other things, all while still maintaining the ability to also produce a printable output version. 

Quarto has tremendous potential for making scientific research more accessible, transparent, reproducible, diverse and fast. Combining Quarto with Julia is in my own experience nothing less than a game changer. For more information feel free to also check out my [blog post](https://www.paltmeyer.com/blog/posts/julia-and-quarto-a-match-made-in-heaven/) on the topic.

## Notes 

While I have used R and R Markdown for many years and therefore owe the folks behind R Studio a tremendous amount of gratitude, I am in no way affiliated with R Studio or any of the developers behind Quarto. Having worked with Quarto and Julia for a few months now, I have just been very happy about the overall experience and would love to share that with the Julia community. Being able to produce all kinds of different outputs from one place is something that I am sure lots of people would be very interested in hearing about. 