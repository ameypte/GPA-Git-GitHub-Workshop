
# **GPA Git & GitHub Workshop Activity**

This repository hosts the activity for the **Git & GitHub Workshop**, along with the website showcasing all the participants' contributions.  

🔗 **Live Website**: [https://ameypte.github.io/GPA-Git-GitHub-Workshop/](https://ameypte.github.io/GPA-Git-GitHub-Workshop/)

---

## **Activity Instructions**  

### 📝 Steps to Contribute:  
1. **Fork this repository**:  
   - Click the **Fork** button on the top-right of this page.  

2. **Clone your forked repository**:  
   ```bash
   git clone https://github.com/ameypte/GPA-Git-GitHub-Workshop.git
   cd GPA-Git-GitHub-Workshop
   ```

3. **Create a new branch**:  
   ```bash
   git branch <your-name>
   git checkout <your-name>
   ```

4. **Update the `data.json` file**:  
   - Open the `data.json` file in any text editor or IDE.  
   - Add your details in the following format under the `"participants"` array:  
     ```json
     {
       "name": "Your Name",
       "year": "Second Year or Third Year",
       "department": "Your Department",
       "idCode": "Your ID Code",
       "feedback": "Your Feedback (optional)"
     }
     ```  
   - Example entry:
     ```json
     {
       "name": "John Doe",
       "year": "Second Year",
       "department": "Information Technology",
       "idCode": "23IF100",
       "feedback": "Great workshop! Learned a lot."
     }
     ```

5. **Commit your changes**:  
   ```bash
   git add data.json
   git commit -m "Added details for <your-name>"
   ```

6. **Push your changes**:  
   ```bash
   git push -u origin <your-name>
   ```

7. **Create a Pull Request (PR)**:  
   - Go to your forked repository on GitHub.  
   - Click **Compare & pull request**.  
   - Submit your PR for review.  

---

## ⭐ **Star the Repository**  
Don’t forget to star this repository to show your support! 🌟  

---

## **Important Notes**  
- Ensure all contributions are valid and follow the given format.  
- Submissions with invalid data or duplicate entries will be rejected.  

🛑 **Deadline**: Submit your PR before the form closes!  

---

## **Feedback & Support**  
If you face any issues or have questions, feel free to reach out.  

Happy Coding! 🚀  
