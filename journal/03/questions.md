# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > | Let's define OOP first. OOP is designing something to fit the objects it is built with, rather changing the objects to fit some other potential component. It's picking the tool for the job rather than picking the tool and making the job fit it. Using a hammer to make a salad might work, but it's going to have errors and no Michelin stars. Programming designed from the objects that comprise it will have fewer errors because it is designed to work with what it will be given and what it will need to do. Fewer errors and more coherent and cohesive development are important. It makes a project manageable and allows for complexity without losing its utility or functionality. 
  
  1. Data abstraction is hiding the data and objects, including functions, the programmer does not want the user to have direct access to. They can interact with it, but only through that layer of abstraction. It's a first step towards protecting the data and methods inside the program.
  
  2. Encapsulating takes the data and methods and bundles it into one unit. This protects the essential parts of the program from being manipulated or used in unintentional ways. It also allows it to be organized and more easily understood for making improvements or changes because it keeps it from being unintentionally changed. Hiding the methods and data in a bundle helps keep the program from being misused. 
  
  3. Inheritance is just what it sounds like, but with classes instead of human possessions. A parent class has a structure and methods which may be inherited by a child class. They may not be utilized the same way since the child class may redefine the methods, but they are based off the ones that came before. 
  
  4. Polymorphism is the final pillar. This means that an object can take many forms. As long as their methods have the same name, different objects can be used interchangeably. |

02. How does `export` differ from `export default`?
  
  > | When exported in default the script exports in strict mode, meaning that it will remain private and hidden. The script must be accessed the same way it's exported (default or not) through the use of an asterisk. |

03. What is Encapsulation?
  
  > | I like to think of encapsulation as a "yours" and "mine" situation, in which you keep private the information you don't want your users to have access to and protect the processes that are necessary, but you also have what they need visible to them. They have theirs, you have yours, and while they interact with each other, they're held separate and communicate with each other without the user being able to access them. You could use _ to designate which processes you don't want them to have, but that's assuming they will respect that as a sign of it being yours. Instead, encapsulation keeps them from even seeing it. It's security, but it's also a way to make sure things aren't broken. You can make changes to the encapsulated data or processes without the user knowing. It's bundled together and held away from them. |

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > | They allow us to keep data private while still allowing us to utilize it.  It's just like a proxy at a city council vote - it's something standing in for something else, with all the same power as the original who doesn't need to be present and visible. You have the handler, which says how the proxy will be used, and the target, which is the object to be proxied. So if Councilman Jamm isn't able to attend or doesn't want to be public, he can nominate Tammy 2 to be his proxy but also control what of his authority she is allowed to use. |

05. What the difference between a `class` and an instance of a `class`?
  
  > | Classes are a template for creating objects, whether that be data or methods or functions. They are a template, or a form, from which an object can be shaped. An instance of a class is one of the objects from that class that has been created. Instance is used to designate that the object has a relationship with a specific existing class, in other words instances are just objects ... which are made with the blueprints of the class. |

06. What is a computed Property?
  
  > | Computed properties are used to dynamically create object properties using an expression in square brackets. They allow data to be added and adhere to the format desired and allow that new data to be accessed and utilized as if it was an object created at the time of the program's coding. It's a set of instructions for what goes where and allows it to be used as it adheres to the desired formatting. The benefits of using computed properties are that the code stays readable and is easier to maintain, the objects are more dynamic and flexible, and the code is more reusable. |

07. What is the purpose of the `MVC` pattern?
  
  > | Model, View, Controller. The purpose is the keep the jobs of keeping data, visualizing, data, and handling the interaction of the user input and the data and visualization. This reminds me of the Single Responsibility of the Solid principles from last week. Delegating specific duties to different parts of the code allows for better troubleshooting and organization. Think of it like a cafeteria lunch. If you're at a cafeteria and you've only got a bowl, you'll end up with a soup every time, everything mixing together and it becomes difficult to manage which bite of food will contain which flavor. But if you've got a divided plate and get the items separated, then you know which flavor you're getting with each bite and it's easier to swap out one if you don't end up liking it. |

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > | Accepting user input and updating the view based on both the user input and the data representation from the model. |

09. What is the job of the `Service` in `MVC`?
  
  > | Performing the business logic. Rather than storing data, it performs the logic. |

10. What is the job of the `Model` in `MVC`?
  
  > | The model handles the data representation. It doesn't handle user input, it doesn't provide the visualization, it doesn't do anything but data and logic involving that data. |
