# greenwood-library-website


```markdown
# Greenwood Community Library Website

1. **Create Repository**
    - *sign in to github*
    - *click on + sign*
    - *click on 'New repository*
    - *initialize repository by adding a README file*
    - *click on create repository*
   ![Create Repository](https://github.com/user-attachments/assets/f8359982-4d52-4281-b250-df7280f14097)

## Cloning repository in vscode terminal

1. **Change Directory to `git-project`**
    _cd git-project_
   ![Change Directory](https://github.com/user-attachments/assets/1aef3674-368b-48dc-b082-55e59e2c9340)

2. **Clone Repository**
    _clone https://github.com/Tango9er/greenwood-library-website.git_
   ![Clone Repository](https://github.com/user-attachments/assets/9dcb165c-f283-4c88-956b-6c09c74ea848)

3. **Change Directory to `greenwood-library-website`**
    _cd greenwood-library-website_
   ![Change Directory](https://github.com/user-attachments/assets/fb57a943-8c48-439e-a7c7-8de58dc57c7d)

## Creating and adding contents to html files

1. **Create Files**
    _touch 'file-name'_
   ![Create Files](https://github.com/user-attachments/assets/5ab1b784-a0c7-4ae8-953b-5c63022de705)

2. **Add Content to `home.html`**
    _vim 'home.html_
   ![Add Content to home.html](https://github.com/user-attachments/assets/653bf141-1717-4ad2-8937-8b1e264882b8)

3. **Add Content to `about_us.html`**
    *vim 'about_us.html*
   ![Add Content to about_us.html](https://github.com/user-attachments/assets/ad5b9ef5-d279-4430-b951-3d016f51b496)

4. **Add Content to `events.html`**
    *vim events.html*
   ![Add Content to events.html](https://github.com/user-attachments/assets/97555bf6-823b-4703-8460-3792975e81d6)

5. **Add Content to `contact_us.html`**
    *vim contact_us.html*
   ![Add Content to contact_us.html](https://github.com/user-attachments/assets/17eef179-12b0-409c-a278-5cc35cc5e48c)

## Stage, commit and push changes to main branch

1. **Stage All Changes**
    *git add .*
    ![Stage Changes](https://github.com/user-attachments/assets/7aadbb57-279c-4bbb-8cf7-14c57460a346)

2. **Commit Changes**
    *git commit -m "This is my first commit"*
    ![Commit Changes](https://github.com/user-attachments/assets/382f4a7a-f24b-4537-9566-613d4b7bf9c8)

3. **Push Changes to the Main Branch**
    *git push origin main*
    ![Push Changes](https://github.com/user-attachments/assets/9eec5fe0-0b03-4d12-bcea-9c7e4d7e5405)

## Working with new Branches

1. **Create a Branch for Morgan**
    *git branch add-book-reviews*
   ![Create Branch for Morgan](https://github.com/user-attachments/assets/0e993544-812d-41ac-9723-c68847dbdfba)

2. **Switch to the `add-book-reviews` Branch**
    *git checkout add-book-reviews*
   ![Switch to Branch](https://github.com/user-attachments/assets/ff1996ad-54fe-4aac-a972-bb1685486f77)

3. **Add New File `book_reviews.html`**
    *touch book_reviews.html*
   ![Add New File](https://github.com/user-attachments/assets/641942d7-652d-4602-8cd9-8d20f0c10dcb)

4. **Add Content to the New File**
    *vim book_reviews.html*
   ![Add Content](https://github.com/user-attachments/assets/963d777a-d8e5-4249-9785-3ebac5789816)

5. **Stage Change**
    *git add book_reviews.html*
   ![Stage Change](https://github.com/user-attachments/assets/76670018-9d14-4d02-b2c6-5b21a4518b77)

6. **Commit Change**
    *git commit -m "Add book review section"*
   ![Commit Change](https://github.com/user-attachments/assets/5f6cd435-a276-4fc9-b9fb-fe603b4ac031)

7. **Push Change to `add-book-reviews` Branch**
    *git push origin add-book-reviews*
   ![Push Change](https://github.com/user-attachments/assets/64761b73-c71b-4bfe-b585-247bff5a179b)

8. **Compare Files Before PR**
    *click on 'compare & pull request'*
   ![Compare Files](https://github.com/user-attachments/assets/c8a7c754-2692-49d4-8322-59076bcd7e0c)

9. **Raise PR for Morgan's Work**
    *click on 'create pull requets'*
   ![Raise PR](https://github.com/user-attachments/assets/e5d91901-4a33-40fa-9b0d-d825a38f431d)

10. **Merge PR for Morgan's Work**
    *click on 'merge pull request'*
    ![Merge PR](https://github.com/user-attachments/assets/4770de4a-5241-4475-86a7-c780c5d00718)

11. **Confirm Merge**
    *click on 'confirm merge'*
    ![Confirm Merge](https://github.com/user-attachments/assets/1757b61a-1b15-48f4-a489-011744d5b966)

12. **Merge Confirmed Successfully**
    ![Merge Confirmed](https://github.com/user-attachments/assets/28856708-2fc2-4166-a9e5-87595235f5de)

## Updating the Main Branch from terminal

1. **Switch to the Main Branch**
    *git checkout main*
   ![Switch to Main Branch](https://github.com/user-attachments/assets/60ac6165-ecd0-4347-bd21-ad99ebcff443)

2. **Pull Changes from `add-book-reviews` Branch**
    *git pull add-book-reviews*
   ![Pull Changes](https://github.com/user-attachments/assets/b8d106b5-38da-4b0e-b494-696d4627f4ea)

3. **Create a New Branch for Jamie**
    *git branch update-events*
   ![Create Branch for Jamie](https://github.com/user-attachments/assets/d1aa7736-4602-402c-92ea-050bc19a6805)

4. **Switch to the `update-events` Branch**
    *git checkout update-events*
   ![Switch to Branch](https://github.com/user-attachments/assets/d4255cf5-c819-4601-a160-148659c9ee01)

5. **Pull Changes from the Main Branch**
    *git pull origin main*
   ![Pull Changes](https://github.com/user-attachments/assets/850bcba5-cc87-42db-b417-c7ae438013e4)

6. **Make Change to `events.html` File**
    *vim events.html*
   ![Make Change](https://github.com/user-attachments/assets/0647f4ee-97d0-48c4-9c0f-b36e49bcb1c9)

7. **Stage Change**
    _git add events.html_
   ![Stage Change](https://github.com/user-attachments/assets/9151b0ed-dd00-476e-8d7c-7d5579801886)

8. **Commit Change**
    _git commit -m "updated events"_
   ![Commit Change](https://github.com/user-attachments/assets/90efd3c5-b63b-4cfc-92b3-c5f71675dd00)

9. **Push Changes to `update-events` Branch**
    *git push origin update-events*
   ![Push Changes](https://github.com/user-attachments/assets/db90d40e-f727-44ea-af6f-24f5f7df5ad8)

10. **Compare Files Before PR**
    *click on 'compare & pull request'*
    ![Compare Files](https://github.com/user-attachments/assets/91c59e42-8a5f-4d59-8a31-f64626ddffe7)

11. **Raise PR for Jamie's Work**
    *click on 'create pull requets'*
    ![Raise PR](https://github.com/user-attachments/assets/17ad0374-a2cf-4de1-aed9-fe4da42c13d5)

12. **Merge PR for Jamie's Work**
    *click on 'merge pull request'*
    ![Merge PR](https://github.com/user-attachments/assets/7e44cb9e-1a3f-4483-a0b7-f20652a6d00e)

13. **Confirm Merge**
    *click on 'confirm merge'*
    ![Confirm Merge](https://github.com/user-attachments/assets/1cd8ea3f-92e7-4309-934d-cb2de68ba641)

14. **Merge Confirmed Successfully**
    ![Merge Confirmed](https://github.com/user-attachments/assets/b6a1d3a2-4c0d-4bd4-847d-ae4148b02656)
```

This Markdown file provides a step-by-step guide with images for each action, making it easy to follow the process of setting up and managing the repository for the Greenwood Community Library website.


