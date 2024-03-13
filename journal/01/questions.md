# Foundations of Web Development
01. In your own words, why do we use Git?
    > | There are several uses for Git. First, it allows people to share files and information across distances, but more importantly it allows us to keep versions of files over time, like drafts or versions used earlier. |

02. In the terminal, what is the command `mkdir` used for?
    > | mkdir is the command to make a new directory in the specified folder.|

03. What is a ***pseudo-class*** and what are some of the most common ones you think you will use?
    > | A pseudo-class is a class that isn't directly applied in the HTML but apply to the circumstances in which the element exists, such as when an action like hovering or clicking occurs.  It's a CSS instruction that makes the element perform or look a certain way when given the proper input. It is not an element in itself. |

04. What is ***specificity*** and how might you use it to your benefit?
    > | Specificity declares the weight of the CSS instruction compared to others, so if it comes into direct competition with another CSS instruction it will choose the one with the most specificity. |

05. What problems do you think you could run into if you over-utilized the `!important` feature?
    > | The added specificity could override the specificity you intend.  Also from a logical standpoint declaring too many things important dilutes the meaning of the word - not everything is the same importance. |

06. What are the three components that makeup a `CSS` rule? <br> Example:

    ```css
        h1 {
            color: rgba(255, 210, 33, .75);
        }
    ```

    > | The first is the element, class, or id. These are also called selectors and they identify parts of the document and tie the next two components to specific elements, classes, or ids identified. The next is the property and value. They determine which part of the CSS will be changed and in which way.  That's the outcome desired.  For example, the above says the largest heading should be comprised of text that is a specific color and opacity. |

07. How do you think good design influences people when visiting a website, and what sorts of things could you convey through design alone?
    > | As a former marketing manager I can say it conveys authority, competence, and value. |

08. What is the purpose of ***wireframing***?
    > | Wireframing is used to create a basic idea of what the document will contain and how it will be organized, like an outline for an essay. They help keep things focused on how the user interacts with the information and what elements and functions will be needed. |

09. Do you think wireframes are worth the time, energy, and effort that they require? Why or Why not?
    > | Yes. Having a plan and knowing how things will come together, at least at a basic level, is necessary to keep your focus and ideas clear. |

10. Define the display `:flex property:`
    > | Flex is the property that tells a container how to handle the different elements within it, on multiple axis. It tells items to behave by appearing in certain areas within a parent element. |

11. What `CSS` properties affect the size of a box model?
    > | Align, Justify, and Flex (and their more specific friends). Align and Justify are on different Axis (X, Y) and Flex is how the content behaves by changing axis. |
