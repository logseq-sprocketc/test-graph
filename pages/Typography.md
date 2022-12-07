- # Heading 1
- ## Heading 2
- ### Heading 3
- #### Heading 4
- ##### Heading 5
- ###### Heading 6
-
- Yellow highlight
  background-color:: yellow
- Red highlight
  background-color:: red
- Pink highlight
  background-color:: pink
- Green highlight
  background-color:: green
- Blue highlight
  background-color:: blue
- Purple highlight
  background-color:: purple
- Gray highlight
  background-color:: gray
-
- [link](https://logseq.com)
  id:: 6390b2d0-281e-4c34-90ab-3eb8a2bad044
- <email@address.com>
- [[Page reference]]
  id:: 6390ab6d-1139-4c8f-b633-38d7598abd8d
- #Tag
- Referenced block
  id:: 6390abdc-4b1a-44aa-8aba-65fbb2d0bc2f
- ((6390abdc-4b1a-44aa-8aba-65fbb2d0bc2f))
- ((invalid-block-reference))
  id:: 6390abd2-737f-4adf-ab90-129ae0bfde0e
-
- __Bold underscore__
  **Bold asterisk**
- _Italic underscore_
  *Italic asterisk*
- ___Bold and Italic underscore___
  ***Bold and Italic asterisk***
- ~~Strikethrough~~
- ^^Highlight^^
-
- > Blockquote
- > Blockquote
  >
  > with multiple paragraphs
- > Blockquotes
  >
  >> Nested
-
- dashes horizontal rule
  ---
  asterisks horizontal rule
  ***
  underscores horizontal rule
  ___
-
- `Code`
- ```
  Code block
  ```
- ```clojure
  (defn setup-viewport-listeners! []
    (when-let [^js vw (gobj/get js/window "visualViewport")]
      (let [handler #(state/set-state! :ui/viewport {:width (.-width vw) :height (.-height vw) :scale (.-scale vw)})]
        (.addEventListener js/window.visualViewport "resize" handler)
        (handler)
        #(.removeEventListener js/window.visualViewport "resize" handler))))
  ```
- $$E = mc^2$$
- | Syntax | Description |
  | --- | ----------- |
  | Header | Title |
  | Paragraph | Text |