Project is created

حذف الفرع محليًا:

git branch -d dev

git branch -d test

حذف الفرع عن بُعد (remote):

git push origin --delete dev

git push origin --delete test

*********************************************
- **Annotated Tags**:
  - Contain extra information like the tagger's name, email, date, and a message.
  - Stored as full objects in Git.
  - Typically used for official releases or versioning.
  - Example:
    ```bash
    git tag -a v1.0 -m "Official release"
    ```

- **Lightweight Tags**:
  - Just a simple pointer to a commit (no additional metadata).
  - Not stored as full objects.
  - Usually used for temporary or internal references.
    ```bash
    git tag v1.0
    ```

 **When to Use Rebase**:

- To clean up the commit history and make it linear.
- To avoid unnecessary merge commits.
- Recommended for local branches **before** merging into the main branch.
- Example:
  ```bash
  git checkout feature
  git rebase main


**How to List Tags**:

To view all tags in your repository:

```bash
git tag


# Deleting Git Tags Locally and Remotely

To delete a Git tag both locally and remotely, follow these steps:

### 1. **Delete the tag locally**

Run this command to delete the tag on your local machine:

```bash
git tag -d <tag_name>

###2. Delete the tag remotely
git push --delete origin <tag_name>

### Add image 
![the dog](path/to/your/img6.jpg)



