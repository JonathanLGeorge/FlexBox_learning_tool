(Flex box notes)

-container notes
flex-direction: row | row-reverse | column | column-reverse

flex-wrap: nowrap | wrap | wrap-reverse

justify-content: flex-start | flex-end | center | spaced-between | spaced-araound | space-evenly

align-items: stretch | flex-start | flex-en | center | baselline

align-content: stretch | flex-start | flex-end | center | space-between | space-around

-item notes

align-self: auto | stretch | flext-start | flex-end | center | baseline

order: 0 | <Integer>

flex-grow: 0 <Integer>

flex-shrink: 1 | <integer> //if this was zero we would notice that if the browser window was smaller, the items that have this property will not shrink

flex-basis: auto | <length>
simply using flex: 0 1 auto is like calling
flex: flex-grow flex-shrink flex-basis

flex: wrap;
this will bring down items to the next row if they cannnot fit on the screen.
