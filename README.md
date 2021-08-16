# CSS Stacking context demonstration

Before exploring stacking context, let's first analyze how positioning in CSS works.

Positioning gives you more control over elements by overriding the browser's normal behavior for element flow.

The five types of positioning are as follows:

1. ```css
   position: static;
   ```

2. ```css
   position: relative;
   ```

3. ```css
   position: absolute;
   ```

4. ```css
   position: fixed;
   ```

5. ```css
   position: sticky;
   ```

---

## Relative position

Relative positioning is quite similar to static positioning except for when the positioned element has taken its place in the normal flow, you can then modify its final position using the properties `top` `right` `bottom` `left`

## Absolute positioning

An absolutely positioned element no longer exists in the normal document flow. Instead, it sits on its own layer separate from everything else. This is helpful when creating very isolated UI features that don't interfere with the layout of other elements on the page.
Absolutely positioned elements will also not positive relative to itself like relative positioning. Absolute positioning specifies the distance the element should be from each of the containing element's sides. For example, `top:30px` would mean sit 30px from the top of the containing element.
