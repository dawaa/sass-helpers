# Fluid typography

#### placeholder.scss
This contains variables which we use in grid.scss

---

#### grid.scss
To clarify on how to get this to work, simple markup could look like this:

````
section
  div flex="row"
    div flex="column sm-4"  /div
    div flex="column sm-4"  /div
    div flex="column sm-4"  /div
  /div
/section
````


#### flex="row" (options)
`div flex="h-center"`
Horizontally center items inside the div
`div flex="v-center"`
Vertically center items inside the div
`div flex="space-between"`
To add space-between
`div flex="row-wrap"`
This one is default already within "row".