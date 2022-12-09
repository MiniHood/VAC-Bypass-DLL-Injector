Injecting a DLL into a process is a common technique used by hackers to gain access to a system and execute code. However, it is also a technique that is often detected by security systems like Valve Anti-Cheat. In general, the best way to avoid detection is to make your injection method as stealthy as possible.

Here are some steps you can take to make your DLL injection less likely to be detected by Valve Anti-Cheat or other security systems:

Use a manual mapping technique. This involves manually loading the DLL into the target process's memory, rather than using the standard Windows API functions like LoadLibrary or LoadRemoteLibrary. This makes it more difficult for security systems to detect the injection, as the DLL is not loaded in the usual way.

Use code obfuscation. This involves using techniques to make your code difficult to understand or reverse engineer. For example, you can use a code obfuscator to rename variables and functions, insert fake code, or encrypt strings in your DLL. This makes it more difficult for security systems to analyze your code and identify it as malicious.

Use a trusted injection method. There are many different ways to inject a DLL into a process, and some methods are more likely to be detected than others. For example, using the CreateRemoteThread method is a common and well-known technique, so it is more likely to be detected by security systems. Instead, try using a less well-known or less commonly used injection method, such as the SetWindowsHookEx method.

Use a trusted source for your DLL. Security systems often maintain a database of known malicious DLLs, and will flag any DLLs that match their entries. To avoid this, make sure to use a DLL that is not known to be malicious, and avoid using DLLs from untrusted sources.

Keep in mind that these steps can only decrease the likelihood of your DLL injection being detected. There is no guarantee that it will not be detected, and security systems are constantly improving their detection methods. The best way to avoid detection is to not engage in activities that are against the rules or terms of service of the game or platform you are using.
