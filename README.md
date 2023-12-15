# RoadMapFrontEnd
This is a RoadMap to ensure that the best Coding Practices And Case Studies are being conducted before Entering into the New Project

## Overview

When creating a roadmap for good development practice, it is important to carefully consider the foundational elements of the project. This includes selecting the package builder, front-end framework, decorator framework, and CSS styling approach.

During the building of the Frontend Application, it is important to choose between the best foundational libraries for different elements of the project. This includes selecting the package builder, front-end framework, decorator framework and the CSS styling approach.

## Framework Fixed (By WenCong)

| Name | Text |
|----------|----------|
| Package Builder | Vite |
| Frontend Framework | React |
| Decorator Framework | Mantine v7.0 |
| Reusable Components | StoryBook |
| Unit Testing | Vitest |
| End to End Testing | Playwright |
| CI/CD Pipeline | GitLab |


## Pre Commits And Coding Practices

We will follow Google Typescript Style to make sure we are up to industry standards when it comes to creating a new project from scratch

## CSS Styling: CSS Modules vs Vanilla Extract

### Case Study: CSS Modules

When it comes to CSS styling, there are different approaches to consider. CSS Modules and VanillaExtract are two popular options.

CSS Modules allow for scoped CSS styles, ensuring that styles only apply to specific components. It helps avoid style conflicts and provides modularity.

### Case Study: Vanilla Extract

VanillaExtract is a CSS-in-JS solution that offers a strongly typed and scalable approach to styling. It integrates well with TypeScript and allows for CSS variables and dynamic theming.

## Converters: All Raw File Converters

### EML Converters

- Displaying EML Converters

### Audio Converters

- Displaying Audio Files
- Text To Speech Function

### Email Converters

- Writing the Header Format with the Sender, Recipient, CC
- Writing the Body of the Email Attachment
- Writing the Footer of the Email Attachment

### PDF Converters

- Showing PDF Content into the Component itself


## Filter Search

### There are no Good Filter Searches for now… Everything is Customizable

**Here's how you can combine these libraries to achieve your desired functionality:**

1. **Design your drag-and-drop interface:** Use React DnD to create draggable components representing search filters.
2. **Add dropdown menus with AND/OR options:** Use Downshift to create dropdown menus within each filter component, allowing users to select the operation for combining with other filters.
3. **Handle query building:** Use Facette to handle the backend logic of building the search query based on the user's selections and chosen operations. This could involve parsing the drag-and-drop order, understanding the chosen operators, and constructing the appropriate SQL or query language format.
4. **Manage data fetching and state:** Use React-Query to manage the state of your search filters and fetch data from your backend based on the dynamic query built using drag-and-drop and operator selections.

**Additional Libraries:**

- **React-Select:** A popular library for building single/multi-select dropdowns, helpful for providing more options for complex filter combinations.
- **React-InputMask:** Useful for formatting user input for specific filter types like dates, numbers, or phone numbers.