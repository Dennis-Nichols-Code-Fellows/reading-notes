# Code 301 - Class 1

## [Component-based architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

1. What is a “component”?
'A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.' -Tutorials point

2. What are the characteristics of a component?

- Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

- Replaceable − Components may be freely substituted with other similar components.

- Not context specific − Components are designed to operate in different environments and contexts.

- Extensible − A component can be extended from existing components to provide new behavior.

- Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

- Independent − Components are designed to have minimal dependencies on other components.

3. What are the advantages of using component-based architecture?

- Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

- Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.

- Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

- Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems. (Tutorials point)

## [What are props?](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)

1. What is “props” short for?
  Properties

2. How are props used in React?
They are used to dynamically update the data of components. They are like arguments for React components.

3. What is the flow of props?

From parent to child.
