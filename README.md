# npm-redux
`npm view @types/redux` has no type definitions, but this description: 

 _'This is a stub types definition for Redux (https://github.com/reactjs/redux). Redux provides its own type definitions, so you don\'t  need @types/redux installed!'._  

But redux's index.d.ts makes some assumptions about the way that I work, which are not true.  This file works properly.  I'll investigate further and make a PR wherever it needs to go, but for now ... 
