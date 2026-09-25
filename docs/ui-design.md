# UI Design

## Typography
Primary font: 'Montserrat', sans-serif
Secondary font: 'Lato', sans-serif

## Color System
Primary: #e16120
Secondary:
Background: #f5f5f5
Text: white
Divider: #f0f0f0
Placeholder text: #A9A9A9
Description: #565656
Close: red
Card: white
Descriptive card: #fcfcfc
#3b9692

## Spacing/gap
Gap: 20px
Margin: 40px
Sub heading letter spacing: 2.5px
Badge padding: 2px 6px
8px 
8px 20px
16px

## Border Radius
Search: 16px
Card: 5px
Badge: 4px

## Font Weight
Sub Heading: 600
700

## Responsive Breakpoints
Desktop:
Tablet:
Mobile:

## Components
- Navbar
- Sidebar
- Header image
- Search bar
- Cards

## External links used
Bootstrap CSS
Bootstrap JS
Font Awesome CSS


Why CSS Grid?
Used for the category card layout because it provides better control over two-dimensional responsive layouts.

Why Bootstrap?
Used for responsive sidebar, navbar components, while custom CSS handles the application's visual identity.

How the list-markers are custom styles?
Default markers are removed using 'list-style:none;' property
Added a 'counter-increment' inside the li
Added 'content' as counter in pseudo element selector and provided necessary styling
Gave display-inline-flex with height and width to get the perfect circle

Mobile table behaviour
Converted the desktop table into a horizontally scrollable container on smaller screens rather than allowing the page itself to overflow.
