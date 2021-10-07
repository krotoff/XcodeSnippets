# XcodeSnippets
My Xcode Code Snippets for an easier life

# What is it?
Snippet is a template of code. I made a few types of these templates:
1. `snipGuardSelf`: use it inside of methods or closures to make a `guard let self = self else { return }` line;
2. `snipPublicVariables` (or Internal/Private/Custom instead of Public, or Types/Functions instead of Variables, and etc.): use it inside your classes/structs to make class section markers like `// MARK: - Public variables`;
3. `snipControllerCreating` (or View/Class instead of Controller): use it on the top level to make class templates (UIViewController subclass, UIView subclass, just a standard class) with all markers.

# Usage
1. Install: copy all \*.codesnippet files from repository to `~/Library/Developer/Xcode/UserData/CodeSnippets`;
2. Use: in Xcode just start type `snip` and select required snippet from suggestions.
