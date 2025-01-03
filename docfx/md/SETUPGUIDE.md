# Setup Guide
---
Detailed guide on referencing any of the packages in your project. Using the `EzSaver` package as an example, the same steps apply to other packages containing an `Assembly Definition Asset` file.
### Adding Package Reference
*After you have imported the package, you need to reference it in your project. If you are not using an `Assembly Definition Asset` in your project*, kindly skip this step.
	
To proceed,

1. Click on your project's `Assembly Definition Asset` file
2. Under `Assembly Definition References` click the `(+)` icon below
3. Search and select the desired package's reference e.g. **EzSaver**, then apply changes below:<br/>
![Img](https://raw.githubusercontent.com/ebukaracer/ebukaracer/unlisted/Global-Images/ASMDEF1.png)

### Calling APIs

>Be sure to include: `using Racer.EzSaver;` or `using Racer.pkg_Name;` to any external class calling any of the package's public APIs. 
	
>An optional demo Scene may be contained in the package to guide you through.

### Useful Resources
- [.asmdef files in Unity](https://bit.ly/3exDWNz) 
- [Scripting Define Symbols](https://bit.ly/3yGVWvS).
