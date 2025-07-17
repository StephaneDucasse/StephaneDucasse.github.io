The site is in the site folder.

The folder generated contains the static HTML produced by 

```
| p |
p := FOPublisher new. 
p baseUri: 'StephaneDucasse.github.io'.
p sourcePath: '/Users/ducasse/Test2/MySite/StephaneDucasse.github.io/site'.
p targetPath: '/Users/ducasse/Test2/MySite/StephaneDucasse.github.io/generated'.
p publish.
```

We should commit the site and the generated folders in the source branch. 
Then the script will push to master only the generated/* files.






