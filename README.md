# Vivaan Social Network Project

**Soical Netowrk App**  
_Create a Website for Cameron that meets his needs._

**Dev:** Vivaan Varma

---

## Task 1: Outline your website

### Project Description

A web forum where people cna talk about **NBA games and players**.  
It is a safe space to talk about players and NBA games and is a welcoming community.  
This will allow a website with a primary focus.

---

## Functional Requirements

- Users can **sign up** and **login**
- There is a **home page** with posts and recent news
- You can **create a post**
- **Share**, **comment**, and **like** posts

---

## Non-functional Requirements

- **Easy to use**
- **Safe and respectful environment**
- **Backed up data**

# UI Design Plan

## Wireframe Sketch

Here is the basic layout of my app (sketched by hand):

**Home page:**  
![Wireframe Sketch](images/wireframe1.png)

**Posting Page:**  
![Wireframe Sketch](images/wireframe2.png)

**Deep dive into posts:**  
![Wireframe Sketch](images/wireframe3.png)

## Themes and Formatting

## Design Choices

| Element         | Choice                                                                 |
|----------------|------------------------------------------------------------------------|
| Colour Palette | Black, white, red – sporty and high contrast, matches NBA theme        |
| Typography     | Oswald for headings, Roboto for body – clean and easy to read          |
| Images/Icons   | NBA players, logos, court backgrounds. Font Awesome for like/share icons |

![Figma Wireframe](images/figmawire1.png)

## Algorithms - Login Page

1. User opens the login page.
2. User enters username and password.
3. System checks if username exists in the database.
   - If NO → Display "User not found" message and stop.
4. If YES → Retrieve stored password for that username.
5. Compare entered password with stored password.
   - If match → Create session token and log user in.  
     Redirect to dashboard/home page.
   - If no match → Display "Incorrect password" message and stop.  
END

## Test Cases

| Test Case  | Feature Tested | Preconditions | Steps | Expected Result |
|--------------|---------------|---------------|-------|-----------------|
| Test 1 | Login with correct credentials | User account exists | 1. Go to login page<br>2. Enter correct username/password<br>3. Click "Login" | Redirect to dashboard |
| Test 2 | Login with wrong password | User account exists | 1. Go to login page<br>2. Enter correct username/wrong password<br>3. Click "Login" | Display "Incorrect password" |

<img src="images/flowchart3.png" alt="Login Flowchart" width="800"/>


Week 5- SQL and Queries
This week, I created mock data and successfully imported it into VS Code using SQLite. I then wrote and tested several SQL queries on the dataset, which allowed me to retrieve and analyze useful information. Through this process, I learned how to manage data in a database environment and gained insights into how queries can be used to answer specific questions.