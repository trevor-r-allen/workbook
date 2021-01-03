# Day 11
__12/14/2020__

## Thoughts on ES6 Modules

### What problem does using exports solve?
Normally, code is only available in the file it is written in, and to use it elsewhere you must rewrite it. With exports you can make code available for import and use in other modules.

### How does 'export' differ from 'export default'?
When using 'export default' there can only be one export for that file. When using regular named exports, multiple mayb be exported and and imported from the same file.

### What is a benefit of using the Module System?
One benefit of the Module System is organization, as smaller files of specific function and purpose can be used. Exporting and importing code between these specific use files also has a positive imact on performance due to certain code not needing to exist in multiple places, or needing to run entire files just to access a specific function or bit of code.

#### Afternoon Lab: [Zookeeper](lablink)
