---
layout: essay
type: essay
title: "Patterns At Play"
# All dates must be YYYY-MM-DD format!
date: 2023-11-30
published: true
labels:
  - Design Patterns
---

Imagine you’re a chef experimenting in the kitchen. You create a versatile liquid mixture that adds flavor to various dishes. At first, you simply refer to it as a “flavorful liquid mixture.” As you cook more, you find the need to create different variations of this liquid mixture to suit different dishes. At some point, it gets really inconvenient to call it a “flavorful liquid mixture” so instead you call it a “sauce.” Over time, the world of sauces expands through other chefs experimenting in their own kitchens, offering a diverse range to enhance different types of cuisine. Knowing about sauces and why you might use them is often helpful; it gives you various options for enhancing a dish, but you can still cook dishes without sauces or you could wind up reinventing them.

Programming design patterns work similarly. They are mostly just names for things that you do where it's easier to name them than it is to explain it every time. They represent best practices evolved over time by experienced developers. You can, of course, build software without explicitly knowing about common patterns, they often emerge naturally as you tackle coding challenges. Design patterns are more or less common paradigms which everyone already uses but might not formally recognize. I (and probably you too) am using design patterns all the time. 
 
Design patterns are akin to the sauces in the kitchen. They offer various options to enhance your code, much like sauces enhance dishes. These patterns are not sought out as specific goals; rather, they materialize as solutions to specific coding problems. Oftentimes I’ll find that whilst coding, I have a particular problem and I’ll find that I’d use a common way to solve the problem. Voila a design pattern emerged. I’ll be writing a for loop and realize it's easier to read as a function inside forEach, which is an application of the Visitor pattern. I’ll be rewriting an if/else tree into a case/switch structure, when you realize it's easier to write individual functions for each condition and place them in an object, using your case text as keys, which is an application of the Strategy pattern. There are definitely some patterns that show up a lot and are full of wisdom. It's often helpful to learn from other software engineers' experience and add those approaches to your own tool belt. 

A design pattern has the best value as a vessel to describe a certain construct for a solution within your code, providing a great way to create or establish a common meta language when talking to other developers. For example, if you've ever gotten really invested into an online game or community, you'll notice that they have their own language when it comes to features or aspects of that game. Having this shared common language lets us explain or explore topics regardless of language, library, or framework.

While design patterns are useful, they're not a gospel to all software development, and if used in the wrong situations can be more hindering than helpful. Patterns are a tool. Use them when it’s relevant, but don’t use them for the sake of using them. Use them when you need a solution to a problem. If there’s something about your code that feels like it could be simplified or improved but you can’t quite put your finger on it, read about some design patterns and see if they might solve the problem you’re having.
