# Greenwood Community Library Website

A collaborative mini capstone project to enhance the Greenwood Community Library website, making it more engaging and informative for visitors.
#
#
## Project Overview
This repository contains the source code for the Greenwood Community Library website. The site aims to provide information about the library, upcoming events, book reviews, and contact details. The project demonstrates collaborative Git workflows between team members.
#
## Development Process with Screenshots
This project was developed collaboratively using Git for version control:

1. **Initial Setup**: Created the base website structure with Home, About Us, Events, and Contact Us pages
2. **Feature Development**:
   - Morgan's contribution: Added a Book Reviews section
   - Jamie's contribution: Updated the Events page with upcoming community events
3. **Integration**: Both features were merged using pull requests with code reviews

## Git Workflow Used

The development process followed a feature branch workflow:

1. Main branch contained the stable, production-ready code
2. Feature branches (`add-book-reviews` and `update-events`) were created for new features
3. Developers worked independently on their feature branches
4. Pull requests were used to review and merge changes back to main
5. Regular synchronization with the main branch ensured all developers had the latest code

## Technologies Used

- HTML5 for structure
- CSS3 for styling
- Git for version control
- GitHub for collaborative development
#
#### Creating the GitHub Repository

![Creating New Repository](./img/1.%20repo%20on%20gh.jpg)

#### Repository Settings

![Repository Settings](./img/2.%20name%20the%20repo%20and%20init%20it%20with%20read%20me%20file.jpg)

#### Cloning the Repository

![Cloning Repository](./img/4.%20clone%20the%20repo%20to%20local.jpg)
#

git clone https://github.com/SylvesterOgaOgaji/greenword-library-website.git
'''
![Cloning Repository](./img/5.%20cloning%20on%20the%20local%20machine.jpg)

![Successfull Cloning](./img/6.%20Cloning%20on%20local%20machine%20sucessful.jpg)
#
###  Navigate to the project directory
cd greenwood-library-website

![navigating to the repo](./img/7.%20navigate%20to%20the%20cloned%20directory.jpg)

![comfirming main branch](./img/8.%20confirming%20the%20branch%20main.jpg)
#
### 2. Creating Base Website Structure
### Creating HTML Files

![Creating HTML Files](./img/9.%20html%20files%20created.jpg)
using the the touch command: 
touch home.html about_us.html events.html contact_us.html
#
### Adding Content to Files
![Adding Content to Files](./img/11.%20edited%20using%20VS%20code.jpg)
#
### Staging Initial Files
![comfirming main branch](./img/12.%20Stagging%20four%20html%20files.jpg)

![comfirming main branch](./img/13.%20stagging%20successful.jpg)
#
# 3. Morgan's Work: Adding Book Reviews
### Creating Morgan's Branch

 ![](./img/15.%20Morgans%20work%20branch%20adding%20book%20review%20is%20created.jpg)

git checkout -b add-book-reviews
#
### Creating all Page
 ![](./img/16.%20book%20reviews.jpg)
 ![](./img/16a.%20book%20reviews%20git.jpg)
 ![](./img/17.%20editing%20about%20us%20using%20nano.jpg)
 ![](./img/17a.%20opening%20about%20us.jpg)
 ![](./img/18.%20opening%20contect%20us.jpg)
 ![](./img/19.%20editing%20home.jpg)
 ![](./img/19a.%20opening%20home.jpg)
 ![](./img/20.%20editing%20events.jpg)
 ![](./img/20a.%20opening%20events.jpg)
#
### Staging Morgan's Changes
 ![](./img/21.%20stagging%20your%20changes.jpg)
git add .
#
### Commiting Morgan's Changes
 ![](./img/22.%20commiting%20your%20changes.jpg)
git commit -m "Add book reviews section"
#
### Pushing Morgan's Changes
![](./img/23.%20pushing%20to.jpg)
git push origin add-book-reviews
#
### Creating Morgan's Pull Request
![](./img/24.%20compare%20and%20pull%20request.jpg)
![](./img/25.%20add%20title%20descrption%20and%20create%20pull%20request.jpg)

### Reviewing Morgan's Pull Request
![](./img/26.%20adding%20the%20pull.jpg)
![](./img/27.%20pull%20request.jpg)
#
### 4. Jamie's Work: Updating Events Page
Switching to Main Branch
![](./img/29.%20switching%20branch%20to%20main.jpg)
git checkout main
#
### Creating Jamie's Branch
![](./img/30.%20creating%20branch%20for%20Jamie.jpg)
git checkout -b update-events
#
### git pull origin main
![](./img/31.%20Event%20update.jpg)
![](./img/32%20opening%20events%20dot%20html.jpg)
#
### Staging Jamie's Changes
![](./img/33.%20stagging.jpg)
git add .
#
### Commiting Jamie's Changes
![](./img/34.%20commiting.jpg)
git commit -m "Update events page"
#
### Pushing Jamie's Changes
![](./img/35.%20pushing.jpg)
git push origin update-events
#
### Creating Jamie's Pull Request
![](./img/36.%20pull%20request.jpg)
![](./img/37.%20creating%20the%20pull%20request.jpg)
#
### Reviewing Jamie's Pull Request
![](./img/38.%20resolving%20conflict.jpg) 
#
### Merging Jamie's Pull Request
![](./img/39.%20resolved.jpg)
![](./img/40.%20resol.jpg) 
![](./img/41.%20ready%20for%20commit.jpg) 
![](./img/42.%20resolved%20and%20ready%20for%20merge.jpg.%20resolved.jpg) 
![](./img/43%20confirming%20merge.jpg.%20resolved.jpg) 
![](./img/44.%20pull%20request.jpg.%20resolved.jpg) 
#
### 5. Final Verification
Switching to Main and Pulling Final Changes
git checkout main
git pull origin main
![](./img/45.%20switching%20to%20main%20branch.jpg)
#
### Verifying All Pages
![](./img/46.%20verification%20of%20book.jpg)
 