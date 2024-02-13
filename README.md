# Reusable String Builder Utility for Unity

## Introduction
The `Reusable String Builder` utility, part of the `com.Klazapp.Utility` namespace, is designed for efficient string manipulation, especially when dealing with a large number of string concatenations or modifications.

## Features
- StringBuilder provides methods like Append and AppendLine for efficiently concatenating strings without creating unnecessary intermediate string objects. This can be particularly useful in scenarios where you need to build a string dynamically, such as constructing log messages or displaying UI text.
- Unlike regular string objects in C#, which are immutable (cannot be changed once created), StringBuilder allows you to modify the contents of the string in-place. You can insert, replace, or remove characters from the string buffer without creating new string objects each time.
  
## Dependencies
To use `Reusable String Builder`, certain dependencies are required. Ensure these are included in your Unity project.
- **Unity Version**: Minimum Unity 2020.3 LTS.
- **Repository**: [LogMessage Unity Singleton](https://github.com/klazapp/Unity-Singleton-Public.git)

## Compatibility
| Compatibility        | URP | BRP | HDRP |
|----------------------|-----|-----|------|
| Compatible           | ✔️  | ✔️  | ✔️   |

## Installation
1. Open the Unity Package Manager (`Window` > `Package Manager`).
2. Click `+`, select `Add package from git URL...`, and enter `https://github.com/klazapp/Unity-Reusable-String-Builder-Public.git`.
3. Unity will download and make the package available in your project.

## Usage
```csharp
Write Something here
```

## To-Do List (Future Features)
- 

## License
This utility is released under the [MIT License](LICENSE).
