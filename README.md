# CTF-Defend-TheWeb-Where-Am-I


## Objective


## 📌 Project Objective – CTF: Defend The Web | Where Am I?

This CTF challenge focuses on analyzing and interpreting HTTP headers to uncover hidden clues about the user's identity or origin. The goal is to understand how web servers process client information and how user-agent data can be used to trace or identify requests. This exercise strengthens practical skills in web security, traffic analysis, and header manipulation — all of which are valuable during reconnaissance and vulnerability assessment in real-world penetration testing scenarios.


## 🧠 Skills Learned

- Strong understanding of HTTP headers and how they reveal client metadata.
- Proficiency in identifying and analyzing user-agent strings for fingerprinting.
- Ability to detect subtle clues in web traffic for reconnaissance and exploitation.
- Enhanced knowledge of web protocols and information disclosure vulnerabilities.
- Development of analytical thinking and attention to detail in cybersecurity challenges.

### 🛠️ Tools Used

- Web browser developer tools used Chrome DevTools for inspecting HTTP headers and request metadata.
- Online user-agent parsers to analyze and decode user-agent strings.
- Proxy tools such as Foxy proxy and Burp Suite for intercepting and manipulating web traffic.
- CTF platform interface for challenge execution and flag submission.
- HTTP debugging tools such as curl for crafting and analyzing custom requests.

## 🧩 Steps I Took to Solve the Challenge

1. **Accessed the Challenge Platform**  
   I logged into the Defend The Web platform and navigated to the “Where Am I?” challenge.

2. **Inspected the Web Request**  
   I opened the browser’s Developer Tools (Network tab) to examine the HTTP request and response headers sent to and from the server.

3. **Identified Key Headers**  
   I looked closely at headers like `User-Agent`, `Referer`, and `X-Forwarded-For` to identify any information leakage or clues related to my identity or origin.

5. **Analyzed the User-Agent**  
   I parsed the `User-Agent` string to understand what information it was exposing about my browser, OS, and device.

6. **Modified Headers (if needed)**  
   Using Burp Suite I experimented with altering or spoofing the headers to test how the server would respond.

   ![image](https://github.com/user-attachments/assets/c70e5cfa-4b5f-4858-b7b2-c3b529f72fe0)


8. **Tested Hypotheses**  
   I refreshed and retried different combinations to observe how changes in headers affected the behavior of the page or the clues shown.

9. **Captured the Flag**  
   Once I understood the information the challenge required (such as disclosing my browser or origin), I entered the correct answer or submitted the flag successfully.

   ![image](https://github.com/user-attachments/assets/01351032-16e7-4448-a2ce-eae53dc7eccd)



