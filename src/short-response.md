# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

## Question 1: Flexbox Basics

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

**A flex container is the parent element that controls the layout of its children. A flex item is any direct child inside that flex container. You make an element a flex container by setting display: flex; in CSS.**

## Question 2: Main Axis vs Cross Axis

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

**In Flexbox, the main axis is the main direction that flex items are placed, which is usually horizontal by default. The cross axis goes the opposite direction, usually vertical by default. justify-content moves items along the main axis, while align-items moves items along the cross axis.**

## Question 3: Flexbox vs Grid

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

**I would use Flexbox when I need to arrange items in one direction, like a navbar or a row of buttons. I would use CSS Grid when I need a two-dimensional layout with both rows and columns. For example, Flexbox is better for a navigation bar, while Grid is better for a full webpage layout with a header, sidebar, main content, and footer.**

## Question 4: The `fr` Unit

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

**The fr unit in CSS Grid means “fraction of the available space.” It helps divide space between columns or rows based on proportions. grid-template-columns: 1fr 2fr 1fr would create three columns where the middle column is twice as wide as the first and third columns.**

## Question 5: Media Queries

What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

**A media query lets CSS apply different styles depending on the screen size or device. They are important for responsive web design because they help websites look good on phones, tablets, and desktops. For example:**

````js
@media (min-width: 768px) {
    body {
        font-size: 18px;
        }
    }
```

## Question 6: Mobile-First Design

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

**Mobile-first design means designing the website for small screens first, then adding styles for larger screens using media queries. This approach makes sure the site works well on phones before making it more complex for desktop. It is usually better than desktop-first because mobile users get a faster, cleaner, and easier experience.**
````
