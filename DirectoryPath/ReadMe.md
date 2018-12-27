This was created in response to:
https://stackoverflow.com/questions/14494747/add-images-to-readme-md-on-github

## Display images from repo using:

### prepend domain: https://raw.githubusercontent.com/ or https://cdn.rawgit.com/
### append flag: **`?sanitize=true&raw=true`**
### use `<img />` tag

#### Eample url works for svg, png, and jpg using:

- **Domain**: `raw.githubusercontent.com/`
- **UserName**: `YourUserAccount/`
- **Repo**: `YourProject/`
- **Branch**: `YourBranch/`
- **Path**: `DirectoryPath/`
- **Filename**: `example.png`
     
Works for SVG, PNG, and JPEG

     - `raw.githubusercontent.com/YourUserAccount/YourProject/YourBranch/DirectoryPath/svgdemo1.svg?sanitize=true&raw=true`


Working example code displayed below after used:

**raw.githubusercontent.com**:

<img src="https://raw.githubusercontent.com/YourUserAccount/YourProject/master/DirectoryPath/Example.png?sanitize=true&raw=true" />

<img src="https://raw.githubusercontent.com/YourUserAccount/YourProject/master/DirectoryPath/svgdemo1.svg?sanitize=true&raw=true" />

**https://cdn.rawgit.com**:

<img src="https://cdn.rawgit.com/YourUserAccount/YourProject/master/DirectoryPath/Example.png" />

<img src="https://cdn.rawgit.com/YourUserAccount/YourProject/master/DirectoryPath/svgdemo1.svg" />


```
**raw.githubusercontent.com**:
<img src="https://raw.githubusercontent.com/YourUserAccount/YourProject/master/DirectoryPath/Example.png?sanitize=true&raw=true" />

<img src="https://raw.githubusercontent.com/YourUserAccount/YourProject/master/DirectoryPath/svgdemo1.svg?sanitize=true&raw=true" />

**https://cdn.rawgit.com**:
<img src="https://cdn.rawgit.com/YourUserAccount/YourProject/master/DirectoryPath/Example.png" />

<img src="https://cdn.rawgit.com/YourUserAccount/YourProject/master/DirectoryPath/svgdemo1.svg" />
```


Thanks:
   - https://stackoverflow.com/a/48723190/1815624
   - https://github.com/potherca-blog/StackOverflow/edit/master/question.13808020.include-an-svg-hosted-on-github-in-markdown/readme.md
