# Jr-Penetration-Tester-Lab
TryHackMe Jr. Pentration Tester - Training Course

# Room 1 - # [Walking an Application: Manually Reviewing a Web Application for Security Issues Using Browser Developer Tools](https://tryhackme.com/r/room/walkinganapplication)

In this room, I developed skills to manually review a website using built-in browser developer tools to identify potential security issues. This hands-on approach is essential for understanding the fundamentals of web application security.

## Tools

The following tools I utilized in this room are accessible in any modern web browser and can typically be found under the "More Tools" section in the browser's settings. Below is a short description of each tool and how I used them in the room.

### **View Page Source**

**View Page Source** is an invaluable tool for penetration testers and security researchers. It allows for an in-depth analysis of the website's underlying structure by displaying the raw HTML (Hypertext Markup Language), CSS (Cascading Style Sheets), and JavaScript code that makes up the webpage. This tool is used to:
- **Analyze Code Structure**: Understand how the webpage is built and identify potential security weaknesses in the HTML, CSS, and JavaScript and overall structure.
- **Find Comments and Metadata**: Extract valuable information from comments and metadata that may reveal internal workings or sensitive information.

### **Element Inspector**

**Element Inspector** allows us to view and interact with the current content of a webpage in real-time. This tool is helpful for debugging websites as it enables:
- **Live Editing**: Temporarily modify HTML and CSS to test changes and debug issues without affecting the live site.
- **Examine Dynamic Content**: Investigate how dynamic content is rendered and identify potential security vulnerabilities in real-time.

### **Debugger**

**Debugger** is intended for debugging JavaScript code. As a security tool, it allows researchers to:
- **Step Through Code**: Execute JavaScript code line-by-line to understand its behavior and identify logical errors or vulnerabilities.
- **Set Breakpoints**: Pause execution at specific points to inspect the state of the application and detect issues that might not be apparent in static code analysis.

### **Network**

**Network** tool provides a wealth of information about network requests made by the webpage. This tool is used to:
- **Monitor Traffic**: Observe all network requests and responses, including HTTP headers, status codes, and payloads.
- **Identify Data Exfiltration**: Detect unauthorized data transfers and potential security breaches by analyzing the nature and destination of network requests.

## How I Applied My Analytical and Forensic Skills Using These Tools

1. **Code Review and Analysis**:
   - **Comments in Code**: By examining comments within the code, I gained insights into the developer's thought process and the functionality of various elements. This can sometimes reveal critical information about the application's logic and potential security flaws.
   - **Hidden Directories and Sensitive Information**: I identified any hidden directories or files that could expose sensitive information. This is crucial for ensuring site confidentiality and protecting against unauthorized access.
   - **Configuration Checks**: I reviewed configurations to ensure they are correctly set up to prevent unauthorized access to sensitive webpages or files. Proper configuration is a key element in maintaining the security posture of an application.

2. **Frameworks and Patch Management**:
   - **Version Verification**: By checking the versions of frameworks and libraries used, I ensured that the website is running the most up-to-date versions, reducing the risk of exploitation from known vulnerabilities. Keeping software updated is a fundamental practice in mitigating security risks.

## Key Skills Highlighted

- **Attention to Detail**: My ability to meticulously review and analyze the source code for potential security issues demonstrates a high level of attention to detail.
- **Analytical Thinking**: Evaluating code comments, configurations, and versions of frameworks requires strong analytical skills to understand the security implications.
- **Forensic Investigation**: Identifying hidden directories and understanding their potential security impact showcases my forensic investigation abilities.
- **Technical Proficiency**: Proficiency with browser developer tools and understanding web technologies like HTML, CSS, and JavaScript are essential skills for any cybersecurity professional.

By mastering the use of these tools, I have developed a solid foundation in web application security, preparing me to identify and mitigate potential vulnerabilities effectively.
