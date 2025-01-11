# **Task: Create Your Own CTF Challenge!**

### **Description**
Put yourself in the shoes of a **CTF challenge creator**! Design a beginner-friendly **CTF question** in any domain of your choice (e.g., cryptography, steganography, web exploitation, or forensics). The challenge should include:

1. A clear **goal** (e.g., find the flag, decode the message, or solve the puzzle).
2. A **hint or description** to guide solvers.
3. A **solution walkthrough** (shared privately with reviewers).
4. A **flag** in the format: `FLAG{your_custom_flag_here}`.

---

### **Requirements**
1. The challenge should be **original** and beginner-friendly.
2. Avoid requiring participants to install complex software. Use freely available tools or online platforms (e.g., CyberChef, online encoders/decoders, etc.).
3. Do **not** include any real-life sensitive information (e.g., IP addresses, passwords, or private keys).
4. Ensure the challenge does not violate participant privacy.

---

### **Submission Guidelines**
1. **All submissions must be made as a pull request** to the `CTF-Submissions` directory in the repository.
2. Your pull request should include:
    - **Challenge Title**: A catchy title for your challenge.
    - **Challenge Description**: A brief description of the task and the objective.
    - **Hints** (if any): Subtle clues to guide solvers.
    - **Flag Format**: `FLAG{your_custom_flag_here}`.
    - **Solution Walkthrough**: A step-by-step explanation of the solution.
    - **Challenge Files**: Any required supporting files (e.g., `.pcap`, encoded text, or images).
3. **File Structure**:
    Your files should be placed in a new subdirectory under `CTF-Submissions` named after your GitHub username. For example:

    ```plaintext
    CTF-Submissions/
    ├── your-github-username/
    │   ├── challenge-description.txt
    │   ├── challenge-files/
    │   │   ├── mystery_message.txt
    │   └── solution-walkthrough.md
    ```

4. Clearly state in your pull request if your challenge belongs to a specific category (e.g., cryptography, web exploitation).

---

### **Example Submission**
#### Challenge Title: *Decode the Mystery!*
- **Description**: A secret message has been encoded. Can you decode it to retrieve the flag?
- **Challenge File**: `mystery_message.txt`
- **Hint**: The encoding might be something ancient. (ROT13)
- **Flag Format**: `FLAG{DECODE_SUCCESS}`
- **Solution Walkthrough**:
  1. Open the file `mystery_message.txt`.
  2. Recognize that the message is encoded using ROT13.
  3. Use an online ROT13 decoder to decode it.

---

### **Privacy Note**
Ensure that your challenge and files do not include any private or sensitive information (e.g., MAC addresses, personal logs, or real-life credentials). Challenges should be created in a controlled, safe, and ethical manner.
