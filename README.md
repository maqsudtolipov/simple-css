# Simple - css styling guide

I created new css writing style for easy lookups. It follows 3 basic rules. SPL (SimPLe) - Size, Position (also position) and Looks

1. First part is all about sizing - **margins**, **paddings**, **height** and **widths**.
2. It is used for position of the element on the screen. Use it for **position** and **display** and their helper tags. It could be also 2 parts separated.
3. All the rest goes here, **fonts**, **colors**, **borders** **etc**.

Example:
```css
.note {
  max-width: 80vw;
  padding: 1rem;

  display: flex;
  align-items: center;
  position: absolute;
  bottom: 3rem;

  font-size: 1.4rem;
  background-color: #121212;
  border-radius: 3px;
}
```
Also see [this project files](https://github.com/maqsudtolipov/spotify-clone/tree/main/client/src) for more use cases.

#keepItSimple - 😉