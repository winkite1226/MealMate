# MealMate
## Commit Types
| Type             | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Feat             | A new feature                                                               |
| Fix              | A bug fix                                                                   |
| Design           | Changing related to UI/UX or visual layout                                  |
| !BREAKING CHANGE | Changing that alter the API and affect the frontend (major version impact)  |
| !HOTFIX          | Urgent fix applied directly, usually outside the normal flow                |
| Docs             | Documentation changes (e.g., README updates)                                |
| Style            | Code style changes (formatting, missing semicolons, etc. — no logic change) |
| Refactor         | Code refactoring that doesn't add a feature or fix a bug                    |
| Test             | Adding or modifying tests                                                   |
| Chore            | Routine tasks (e.g., build process, package updates, minor scripts)         |
| Merge            | Merging commits (e.g., branch merges)                                       |
| Comment          | Adding or modifying comments                                                |
| Rename           | Renaming files, variables, or components                                    |
| Remove           | Deleting files, features, or code that is no longer used                    |
| Perf             | Improving performance                                                       |
| Ci               | Continuous Integration or deployment changes                                |
| Init             | Initial commit or project setup                                             |<br />

## Wireframe
<details>
<summary> Wireframe </summary>
<div markdown="1">
  
![로그인 화면](https://github.com/user-attachments/assets/b17bc0db-4fae-456d-9007-714b89dd43d4)
![회원가입 화면](https://github.com/user-attachments/assets/36b70a46-636a-4bcd-9dea-18e92bbc81af)
![메인화면](https://github.com/user-attachments/assets/e441877c-1d8a-4f3c-b6f2-c3ce936add2a)
![매칭된 약속 화면](https://github.com/user-attachments/assets/39f98345-d102-4b13-b109-42d6ae33a255)
![지도 화면](https://github.com/user-attachments/assets/42d03c74-9cee-48ff-8ccc-18b5f45a1454)
![매장정보](https://github.com/user-attachments/assets/70f8c85a-d3ca-44dc-b4ca-bba440194ac9)
![Android Large - 2](https://github.com/user-attachments/assets/d8fc1327-433d-4918-8695-13aa1f51f7b4)
![Android Large - 1 (1)](https://github.com/user-attachments/assets/1a0290e3-ec51-4615-93d2-d2e60e714ecf)

</div>
</details>

## Database
<details>
<summary> Database </summary>
<div markdown="1">
  
![MyProject](https://github.com/user-attachments/assets/a79a36a3-7251-4a94-b07b-730485af293a)


</div>
</details>

## Functional Specification
<details>
<summary> Signup & Signin </summary>
<div markdown="1">
  
  - Signup for users(Signup ID, Password, Email, Name, Phone number)
  - Validate for duplicate Signup ID, Email
  - Verification code with user's email
  - Signup ID must be at least 5 characters and at most 20 characters, and must include both English and numeric characters
  - Password must be at least 8 characters and at most 16 characters, and must include all English, numeric, and special characters
  - The password input and password re-type values must be matched
  - Signin using JwtToken authentication
  - Signin with Social media(Google, Kakao, Naver)

</div>
</details>

<details>
<summary> Register new plan for eating </summary>
<div markdown="1">

- Show map with restaurants pointed
    - User can get restaurants information by page up
    - User location based using GPS
- Two input forms for location, date&time
- Three input forms for limitation the number of people, what to eat, what to talk about
- As soon as user makes a plan for eating, a chat room is created and user is taken there.
    
</div>
</details>

<details>
<summary> My page </summary>
<div markdown="1">

- Show profile information(Profile image, Signin ID, Email, Name, Phone number, Hobby, MBTI)
- Edit profile information
    - Profile image, Phone number, Country, Hobby, MBTI
    - save existing content if no changes are made
- Show the articles I wrote
- Show the comments I wrote
- Show the chatrooms of plans for eating I'll participate in

</div>
</details>
