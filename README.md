The site is in the site folder.
It generates the site at https://stephaneducasse.github.io

The folder generated contains the static HTML produced by 

```
| p |
p := FOPublisher new. 
p baseUri: 'StephaneDucasse.github.io'.
p sourcePath: '/Users/ducasse/Test2/MySite/StephaneDucasse.github.io/site'.
p targetPath: '/Users/ducasse/Test2/MySite/StephaneDucasse.github.io/generated'.
p publish.
```






