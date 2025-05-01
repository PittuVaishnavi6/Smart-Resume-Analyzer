# Smart Resume Analyzer (Java + Spring Boot)

This is a beginner-friendly web application built with **Java** and **Spring Boot**. It helps analyze resumes and gives smart suggestions.

## What It Does

- Shows a simple and clean homepage in your browser
- Built using Java backend + HTML frontend
- You can customize the webpage by editing `index.html`

---

## How to Run This Project on Your Computer

### 1. Prerequisites

Make sure these are already installed on your PC:

- Java 21 (JDK)
- [VS Code](https://code.visualstudio.com/) or any code editor
- Maven (optional – only needed if you want to build manually)

---

### 2. Steps to Run

1. **Clone or Download the Project**
   - Click the green **"Code"** button on GitHub → Download ZIP → Extract it  
   *or*  
   - Run this command in Command Prompt or terminal:
     ```bash
     git clone https://github.com/PittuVaishnavi6/Smart-Resume-Analyzer.git
     ```

2. **Open the Folder in VS Code**
   - Open VS Code
   - Go to **File > Open Folder** and select the project folder

3. **Check the HTML Page**
   - Open the file:  
     `src > main > resources > static > index.html`
   - You can edit this HTML to change the look of your webpage

4. **Run the Application**
   - Open the terminal in VS Code (or Command Prompt in your folder)
   - Run this command:
     ```bash
     ./mvnw spring-boot:run
     ```
     (If you're using Windows, you can also use: `mvn spring-boot:run`)

   - After a few seconds, you’ll see something like:
     ```
     Tomcat started on port 8080
     ```

5. **View the Webpage**
   - Open your browser
   - Type this in the address bar:
     ```
     http://localhost:8080
     ```
   - You’ll see your custom webpage loaded!

---

### 3. Having Issues?

- **Port 8080 already in use?**  
  Edit this file: `src/main/resources/application.properties`  
  Add this line:
  ```properties
  server.port=8081
  You need to go to a browser (like Chrome or Edge) and visit http://localhost:8081 because Spring Boot runs your web application on a local web server, not inside VS Code or the terminal.

Your code creates a web page, and the only way to see and interact with web pages is through a web browser — just like how you open any normal website.
  

