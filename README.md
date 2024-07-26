# greenwood-library-website


```markdown

# Greenwood Community Library Website

## Creating a Repository

1. **Create Repository**
    - **Sign in to [GitHub](https://github.com)**.
    - Click on the `+` icon in the top right corner.
    - Select **New repository**.
    - Check the box to **Initialize this repository with a README**.
    - Click **Create repository**.
    ![Create Repository](https://github.com/user-attachments/assets/f8359982-4d52-4281-b250-df7280f14097)
   
     **Note**: Make sure your repository name is descriptive and relevant.

## Cloning the Repository in VSCode Terminal

1. **Navigate to the `git-project` Directory**
    ```bash
    cd git-project
    ```
    ![Change Directory](https://github.com/user-attachments/assets/1aef3674-368b-48dc-b082-55e59e2c9340)

2. **Clone the Repository**
    ```bash
    git clone https://github.com/Tango9er/greenwood-library-website.git
    ```
    ![Clone Repository](https://github.com/user-attachments/assets/9dcb165c-f283-4c88-956b-6c09c74ea848)

3. **Navigate to the Repository Directory**
    ```bash
    cd greenwood-library-website
    ```
    ![Change Directory](https://github.com/user-attachments/assets/fb57a943-8c48-439e-a7c7-8de58dc57c7d)

     **Tip**: _Verify the repository directory with `ls` command to ensure you are in the right folder._

## Creating and Adding Content to HTML Files

1. **Create New Files**
    ```bash
    touch home.html about_us.html events.html contact_us.html
    ```
    ![Create Files](https://github.com/user-attachments/assets/5ab1b784-a0c7-4ae8-953b-5c63022de705)

     **Note**: Ensure that the file names are exactly as required.

2. **Edit `home.html`**
    ```bash
    vim home.html
    ```
    ![Add Content to home.html](https://github.com/user-attachments/assets/653bf141-1717-4ad2-8937-8b1e264882b8)

3. **Edit `about_us.html`**
    ```bash
    vim about_us.html
    ```
    ![Add Content to about_us.html](https://github.com/user-attachments/assets/ad5b9ef5-d279-4430-b951-3d016f51b496)

4. **Edit `events.html`**
    ```bash
    vim events.html
    ```
    ![Add Content to events.html](https://github.com/user-attachments/assets/97555bf6-823b-4703-8460-3792975e81d6)

5. **Edit `contact_us.html`**
    ```bash
    vim contact_us.html
    ```
    ![Add Content to contact_us.html](https://github.com/user-attachments/assets/17eef179-12b0-409c-a278-5cc35cc5e48c)

     **Reminder**: _Save your changes in `vim` by typing `:wq` and pressing Enter._

## Staging, Committing, and Pushing Changes to the Main Branch

1. **Stage All Changes**
    ```bash
    git add .
    ```
    ![Stage Changes](https://github.com/user-attachments/assets/7aadbb57-279c-4bbb-8cf7-14c57460a346)

     **Tip**: _Use `git status` to review which files have been staged._

2. **Commit Changes**
    ```bash
    git commit -m "This is my first commit"
    ```
    ![Commit Changes](https://github.com/user-attachments/assets/382f4a7a-f24b-4537-9566-613d4b7bf9c8)

     **Tip**: _Write concise commit messages that describe the changes._

3. **Push Changes to the Main Branch**
    ```bash
    git push origin main
    ```
    ![Push Changes](https://github.com/user-attachments/assets/9eec5fe0-0b03-4d12-bcea-9c7e4d7e5405)

     **Note**: _Ensure you're pushing to the correct branch to avoid conflicts._

## Working with New Branches for Morgan

1. **Create a Branch for Morgan**
    ```bash
    git branch add-book-reviews
    ```
    ![Create Branch for Morgan](https://github.com/user-attachments/assets/0e993544-812d-41ac-9723-c68847dbdfba)

2. **Switch to the `add-book-reviews` Branch**
    ```bash
    git checkout add-book-reviews
    ```
    ![Switch to Branch](https://github.com/user-attachments/assets/ff1996ad-54fe-4aac-a972-bb1685486f77)

3. **Add New File `book_reviews.html`**
    ```bash
    touch book_reviews.html
    ```
    ![Add New File](https://github.com/user-attachments/assets/641942d7-652d-4602-8cd9-8d20f0c10dcb)

4. **Edit `book_reviews.html`**
    ```bash
    vim book_reviews.html
    ```
    ![Add Content](https://github.com/user-attachments/assets/963d777a-d8e5-4249-9785-3ebac5789816)

5. **Stage the New File**
    ```bash
    git add book_reviews.html
    ```
    ![Stage Change](https://github.com/user-attachments/assets/76670018-9d14-4d02-b2c6-5b21a4518b77)

6. **Commit the New File**
    ```bash
    git commit -m "Add book review section"
    ```
    ![Commit Change](https://github.com/user-attachments/assets/5f6cd435-a276-4fc9-b9fb-fe603b4ac031)

7. **Push Changes to the `add-book-reviews` Branch**
    ```bash
    git push origin add-book-reviews
    ```
    ![Push Change](https://github.com/user-attachments/assets/64761b73-c71b-4bfe-b585-247bff5a179b)

8. **Compare Files Before Pull Request**
    - Go to GitHub and click on **Compare & pull request**.
    ![Compare Files](https://github.com/user-attachments/assets/c8a7c754-2692-49d4-8322-59076bcd7e0c)

9. **Raise a Pull Request for Morgan's Work**
    - Click on **Create pull request**.
    ![Raise PR](https://github.com/user-attachments/assets/e5d91901-4a33-40fa-9b0d-d825a38f431d)

10. **Merge Pull Request for Morgan's Work**
    - Click on **Merge pull request**.
    ![Merge PR](https://github.com/user-attachments/assets/4770de4a-5241-4475-86a7-c780c5d00718)

11. **Confirm the Merge**
    - Click on **Confirm merge**.
    ![Confirm Merge](https://github.com/user-attachments/assets/1757b61a-1b15-48f4-a489-011744d5b966)

12. **Merge Confirmed Successfully**
    ![Merge Confirmed](https://github.com/user-attachments/assets/28856708-2fc2-4166-a9e5-87595235f5de)


## Updating the Main Branch in VSCode Terminal

1. **Switch to the Main Branch**
    ```bash
    git checkout main
    ```
    ![Switch to Main Branch](https://github.com/user-attachments/assets/60ac6165-ecd0-4347-bd21-ad99ebcff443)

2. **Pull Changes from `add-book-reviews` Branch**
    ```bash
    git pull origin add-book-reviews
    ```
    ![Pull Changes](https://github.com/user-attachments/assets/b8d106b5-38da-4b0e-b494-696d4627f4ea)

    **Note**: _Regularly pull changes from the main branch to stay updated with the latest changes._

## Working with New Branches for Jamie

1. **Create a New Branch for Jamie**
    ```bash
    git branch update-events
    ```
    ![Create Branch for Jamie](https://github.com/user-attachments/assets/d1aa7736-4602-402c-92ea-050bc19a6805)

2. **Switch to the `update-events` Branch**
    ```bash
    git checkout update-events
    ```
    ![Switch to Branch](https://github.com/user-attachments/assets/d4255cf5-c819-4601-a160-148659c9ee01)

3. **Pull Changes from the Main Branch**
    ```bash
    git pull origin main
    ```
    ![Pull Changes](https://github.com/user-attachments/assets/850bcba5-cc87-42db-b417-c7ae438013e4)

4. **Make Changes to `events.html` File**
    ```bash
    vim events.html
    ```
    ![Make Change](https://github.com/user-attachments/assets/0647f4ee-97d0-48c4-9c0f-b36e49bcb1c9)

5. **Stage the Changes**
    ```bash
    git add events.html
    ```
    ![Stage Change](https://github.com/user-attachments/assets/9151b0ed-dd00-476e-8d7c-7d5579801886)

6. **Commit Changes**
    ```bash
    git commit -m "Updated events"
    ```
    ![Commit Change](https://github.com/user-attachments/assets/90efd3c5-b63b-4cfc-92b3-c5f71675dd00)

7. **Push Changes to the `update-events` Branch**
    ```bash
    git push origin update-events
    ```
    ![Push Changes](https://github.com/user-attachments/assets/db90d40e-f727-44ea-af6f-24f5f7df5ad8)

8. **Compare Files Before Pull Request**
    - Click on **Create pull request**.
    ![Compare Files](https://github.com/user-attachments/assets/91c59e42-8a5f-4d59-8a31-f64626ddffe7)

9. **Create a Pull Request (PR) for Jamie's Work**
    - Click on **Create pull request**.
    ![Raise PR](https://github.com/user-attachments/assets/17ad0374-a2cf-4de1-aed9-fe4da42c13d5)

10. **Merge the Pull Request**
    - **Action**: Click on **Merge pull request**.
    ![Merge PR](https://github.com/user-attachments/assets/7e44cb9e-1a3f-4483-a0b7-f20652a6d00e)

11. **Confirm the Merge**
    - **Action**: Click on **Confirm merge**.
    ![Confirm Merge](https://github.com/user-attachments/assets/1cd8ea3f-92e7-4309-934d-cb2de68ba641)

12. **Merge Confirmed Successfully**
    ![Merge Confirmed](https://github.com/user-attachments/assets/b6a1d3a2-4c0d-4bd4-847d-ae4148b02656)

```