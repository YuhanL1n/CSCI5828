# Homework 1

**team members: Liangjun Song, Zhenguo Chen, Yuhan Lin**

**1. Define the term essential difficulties as it is used by Brooks. 
Provide background and context with your answer and at least one 
example of an essential difficulty.**

    Essential difficulties are those difficulties that are inherent,
    intrinsic and part of the nature of software engineering. When 
    we are doing a software project, no matter what tools we choose,
    we would always encounter some problems, such as complexity, 
    conformity, changeability and invisibility problems. To make 
    a specification or design a software, we need to consider those
    properties since they are inherent in the nature of software.
    For instance, users or customers are likely to make changes
    to their requirements, even an arbitrary change, which would
    require the change of software. Customers may not require your
    software to support opening a .jpg file yesterday. Then, they 
    suddenly change their mind and ask for this new feature.
    
**2. Define the term accidental difficulties as it is used by Brooks.
 Provide background and context with your answer and at least one 
 example of an accidental difficulty.**

    Accidental difficulties are those difficulties related to the 
    production of software. Accidental difficulties may differ 
    depending on the development tools we are using. By switching 
    among different tools, we may switch from one set of problems 
    to another set of problems. For instance, when developing a 
    software, you may choose C++ as your programming language, then 
    you feel your development progress is slow and decide to choose 
    Python. After switching to Python, you may face the problem of 
    runtime speed. These problems may exist, but they are not inherent 
    in the nature of software. You may change your editor to solve
     a problem, then you may face a new one.

**3. List and briefly describe the four essential difficulties of developing
 software systems that Brooks identifies. Provide additional examples
 of each type of the four essential difficulties.**

    Complexity: Software entities are complex, and the number and 
    types of the parts increase exponentially with the size of a 
    system increasing. And the complexity of the application away 
    can’t be abstracted away. For example, if you are developing a
    large software system with lots of different modules, the amount 
    of interactions between these modules is huge, and it’s also
    very difficult to test through them.

    Conformity: Software should conform when arbitrary changes happen.
    For example, the software is required to be able to integrate 
    with legacy systems.		

    Changeability：Software are asked to change frequently and constantly.
    For example, nearly all popular applications we are now using on
    smartphones are updated very frequently, like once a week.

    Invisibility: It’s difficult to design graphical displays of 
    software that convey meaning to developers, it’s also hard to
    get overview with details of the software at the same time. 
    For example, UML contains 13 different diagram types so the 
    documentation needs 13 aspects of the software to make itself
    clear.

**4. Define what Brooks means by a silver bullet and reconstruct his 
argument as to why he believes there is no silver bullet for software
 engineering.**
    
    A single technique or technology that by itself can deliver one 
    order-magnitude improvement to some aspect of software development.
    Brooks believe that there are two types of difficulties, essential
    and accidental. Most techniques are used to go over with accidental 
    difficulties, which is only along with this specific software 
    or this specific field. But for the essential difficulties which
    exist in the whole software engineering area, they are unable to
    solve it. What’s more, in order to improve software development 
    significantly, a lot of effort on the accidents of software engineering
    should be put while Brooks think this is even impossible. 
    Because when trying to solve the old problems, the new tool or 
    technique will introduce new ones so it’s not achievable to reduce
    the accidental problems to very little.  

**5. In lecture, software engineering's relationship to computer science 
was described by analogy by discussing the differences between a chemist
 (chemistry) and a chemical engineer (chemical engineering). Define 
 software engineering and its relationship to computer science; make 
 use of the chemist vs. chemical engineer analogy when answering this question.**

    In the real world, there are a lot of scientific truth about the
    world. The term ‘Engineering’ is more like a work to use those 
    facts, truth and rules to build something that is practical and 
    can be used by others under certain constraints. Take the example 
    of chemist and chemical engineer into consideration. A chemist 
    may find a material that is extremely hard and stable. Once chemist 
    discovers this fact, a chemical engineer could make use of it 
    in the real world application. So it is to the computer science 
    and software engineering. A computer scientist could invent an 
    algorithm that is fast, and a software engineering could use it
    in their software. In a word, theories are created or found by 
    the computer scientists. Software engineering is an area that 
    make use of those theories in production scientifically and practically.

**6. In lecture, we discussed the importance of the following concepts
 to software engineers: abstractions, conversations, specification, 
 translation, and iteration. Define each of these concepts as they 
 are related to software engineering and discuss their importance.**
    
    Abstractions: **break a big problem down into small pieces and 
    makes it understandable to others.**
    Usually, the software will have a lot of functionalities. It 
    could be useful to use abstractions to break down the problem 
    and solve them one by one.

    Conversations: **communicate with customers and other developers to solve the problems.**
    In software engineering, good conversations are necessary. We 
    have to talk to the customer to find out what they need. We also 
    need to ‘talk’ to other developers so that we can understand they
     abstractions(By reading their documentation).

    Specification: **specify everything that is related to the project.**
    Same as engineering in other industrials, everything should be well 
    specified in software engineering. The computer is something really 
    precise. In most of the case, a single wrong specification in software
    development can make the whole thing wrong.

    Translation: **solve numbers of problems to solve a bigger problem in a higher level.**
    In software engineering, engineers usually break a big problem into
     small problems and solve those small problems one by one, so the 
     final problem is workable on the human level.

    Iteration: **do the work step by step until it is done.**
    A good software engineer always do the work iteratively
