# What is open data?

So what is open data anyway?

## Two definitions of open data

>Open data is data that anyone can access, use and share. 

This is [the Open Data Institute definition](https://theodi.org/what-is-open-data) of open data. It's intended to provide a simple definition that is accessible to a wide audience. As an elevator pitch it condenses the idea into a single sentence.

As a definition it works very well. It fits in a tweet and works well on a presentation slide. But when using it I always immediately unpack the defintion in order to provide more context. That usually goes along the lines of the following:

By _access_, we mean that the data is available online in some form. You can point to it, download it, or query it in some way. We'll explore the various ways in which data can be published and accessed when we ask: "How do we publish and discovery datasets?"

By _use_, we mean that data isn't simply presented in a format that allows it to be read, e.g. in a document. Reading is just one, albeit important, form of use. The data needs to be made available in a form that allows it to be re-purposed or analysed. In practice this means that open data should be published in a machine-readable format, that allows it to be interpreted, manipulated or visualised using a variety of tools and programming languages.

And by _share_, we mean that we can do more than just use the data ourselves. After it has been corrected, transformed, enriched or aggregated we should have permission to re-publish it for anyone else to use. Permission to work with data can be given in various ways. But the best practice is to publish data under an open licence that explicitly states what we are permitted to do with it. We will look more closely at how open licences when we think about "How do we enable reuse of data?".

But what do we mean by allowing _anyone_ to do that? Answering that question will also be covered in later chapters. But the important aspect to draw out first is that _anyone_ means citizens, individuals, developers, researchers and commercial organisations. Open licences do not place restrictions around who is doing the accessing, using and sharing of data. If those restrictions exist, then it is not open data.

Now, while the ODI definition provides a useful jumping off point for exploring the ideas around open data, it does gloss over a number of important aspects. For example, there are many different ways in which data can be published in machine-readable formats. But some of those formats would require users to have access to specific software or applications in order to actually work with the data. This limits reuse to those who can afford to pay, or otherwise have access to the necessary tools.  

For a more complete definition of open data we can turn to the [Open Definition](http://opendefinition.org/). The summary of the Open Definition is similar to that proposed by the ODI:

>Open data and content can be freely used, modified, and shared by anyone for any purpose

But [the full Open Definition](http://opendefinition.org/od/2.1/en/) goes further, defining a set of principles that help to define "openness" with respect to data and content. These principles are intended to be a reference point that helps to clarify what it means for information to be open. The definition is relatively short and I encourage you to read it in full. But, to summarise, the open definition clearly states that for a work to be open it must:

* be in the public domain, or published under an open licence
* must be available as a whole, should be available online and any costs for accessing it should be reasonable one-off reproduction costs
* must be machine-readable, allowing the work to be easily accessed and modified
* be in an open format that can be accessed using free or openly licensed software

The definition also spells out the permissions that a reuser must have in order for the work to be open. They should be able to:

* use the information themselves
* redistribute it to others
* modify it, in any way
* extract portions of it, e.g. for distribution
* aggregate it with other datasets
* use it regardless of who they are, or what organisation they work for
* pass the data on under the same terms
* not be constrained by their intended purpose, e.g. by limiting reuse for research purposes
* be able to do all of the above for free

The definition also spells out the acceptable restrictions on what reusers are required to do. These include:

* attributing the source of the data
* preserving the integrity of the original, e.g. by requiring users to give a new name to their modified version
* requiring new or modified copies to use the same licence
* requiring that copyright notices are preserved

This provides a much clearer scope for what constitutes an openly licensed data. But even with reference to this more detailed list of requirements there is still room for reasonable debate about their interpretation. 

For example, it is generally accepted that "must be provided as a whole" means that open data should be available in bulk, as a download. But its not clear whether this means that the data has to be available as a single download, or whether multiple files are acceptable. Avaiable "as a whole" might not be feasible in some contexts, e.g. where the open data is a stream of sensor readings and no database of previous readings is available. In some cases the sheer scale of some datasets mean that they may not be readily accessible without incurring significant cost and/or time investments by both publisher and consumer.

Another example is the reasonable requirement that reusers should attribute the sources of their data. As we'll discuss in a later chapter, attribution is an important part of the open data ecosystem. It should be something we do as a community even if there aren't explicit requirements to do so. But attribution requirements themselves can be unnecessarily onerous. For example stating that an attribution must be displayed in a certain way, e.g. appear prominently on every page of an application, or use a minimum font size, can make it awkward for reusers. Especially when data might end up in mobile applications, embedded devices or other equipment. 

In both cases its clear that a reasonable interpretation may need to be made. It might be difficult to put a single, hard definition to "openness" that we can measure everything against. But the open definition does an excellent job of defining the key characteristics of open. 

### Informal definitions of "open"

Does it really matter if a dataset is formally open? I've seen people refer to a dataset as being "open data" when any of the following are true:

* it’s on the web
* it’s free to use
* it’s published under an open licence
* it’s published under a custom licence, which limits some types of use (usually commercial, often everything except personal)
* it’s free to use, so long as you do so within a particular application or platform

Informally, open is often synonmyous with "accessible" or "public", regardless of what licensing is applied to the data, if any. Depending on the needs of the user, some restrictions might be fine. A clause prohibiting commercial use is irrelevant if you're using the data for personal or research purposes.

So should we worry to much about definitions and instead just focus on making more data available, regardless of licensing? Surely we can trust users to clarify whether their specific form of reuse is permitted? 

While at times it can seem like nit-picking, I think its important to try to maintain a clear definition of what is and isn't open data. There are several reasons for this.

We know that people rarely pay attention to terms and conditions. No-one reads the small print. It could be harmful to the open data movement if there were legal challenges over the use or misuse of "open data". If the idea becomes tarnished with uncertainty and doubt then this will be used as an argument for not releasing data or doing so only under very restrictive agreements.

It is the freedoms and permissive uses of open data which is its real strength. Through this it becomes a public good and can be beneficial to all aspects of society. 

For those that do pay attention to licensing, lack of clarity around permitted uses will discourage commercial uptake of open data, especially by organisations that are concerned around the potential risks of using third-party data. While commercial actors are not essential for open data to be a success in all sectors, as we will see in a later chapter, "commercial use" may include charities and similar types of organisations.

### Open data in context

The principles of opennness, sharing and collaboration have been having an impact in a number of disciplines and sectors for some years. Open data is perhaps best viewed as a natural progression that includes:

* Open source - the collaborative creation and maintenance of free software
* Open content - the publication of openly licensed, free content in the form of text, images, movies and music
* Open access - applying open licences to the outputs of academic research to enable it to benefit a wider audience of researchers

The common elements to all of these include:

* sharing of outputs under open licences to enable use by the widest possible audience
* remixing and repurposing of content to create new works, products or solve new challenges
* collaborative production
* collaborative maintenance

These have all been enabled by the web as it provides a common environment to support the publication and sharing of openly licensed materials, and the collaboration tools that enable communities around the world to come together to tackle problems. Open data is a key raw material in this process. As is the open source software used to manipulate it.

Collectively this type of collaborative action can be referred to as "open innovation".

However I see "open innovation" as just one activity that benefits from The Commons. 

The Commons consists of the wealth of openly licensed content, software and data that we are creating as a society. Open innovation is a means of using that to solve a variety of local and global challenges by enabling better collaboration between a variety of organisations. 

## Open data: defined

Use the ODI definition but defer to the open definition for further exploration


