# GitLab and GitHub mirror repository
## :round_pushpin: Introduction
Repository mirroring is a feature that allows automatic synchronization of code between two Git platforms such as GitLab and GitHub.

It ensures that when changes are made in one repository, the same changes are automatically updated in the other repository without manual effort.

##  :construction: Architecture Diagram

![Reference Image](/img/Architecture.png)

## :bulb: Deployment Steps.
### Step 1: Open GitLab & New project

![Reference Image](/img/img1.png)

### Step 2: Import all repository
- Import project
- GitHub
- Import repository
  
![Reference Image](/img/img2.png)

![Reference Image](/img/img3.png)

### Step 3: Create GitLab mirror Repository / Project
- Create blank project
  
![Reference Image](/img/img4.png)

- Project name
- Project URL
- Initialize repository with a README (check in)
- Visibility level (public)

![Reference Image](/img/img5.png)

- Create project
  
![Reference Image](/img/img6.png)

### Step 4: Create GitHub mirror Repository
- New Repository
- Repository Name
- add description
- Add README (ON)
- Create Repository

![Reference Image](/img/img7.png)

### Step 5: Create token
- Settings
- Developer settings
- Personal access tocken
- tocken (classic)
- Generate new token
- Name the token
- Generate token

![Reference Image](/img/img8.png)

### Step 6: Mirroring repositories in GitLab
- Setting
- Repository
- Mirrorng repository
- Add new
- GitHub repository URL
- User name
- Password (token)
- Mirror repository

![Reference Image](/img/img9.png)


### Step 7: Clone repository in local machine

![Reference Image](/img/img10.png)

### Step 8: Open folder in VS Code and push the file
```bash
git add .
git commit -m "added index.html page"
git push 
```

![Reference Image](/img/img11.png)

## Result 1: Display file in the GitLab Project

![Reference Image](/img/img12.png)

## Result 2: Display file on the GitHub Repository

![Reference Image](/img/img13.png)


## 📌 Summary

Repository mirroring is a feature that automatically synchronizes code between GitLab and GitHub. When changes are made in one repository, the same updates are reflected in the other repository without manual copying.