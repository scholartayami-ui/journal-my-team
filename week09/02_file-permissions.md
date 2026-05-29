# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot
<img width="5712" height="4284" alt="image" src="https://github.com/user-attachments/assets/aa2e1112-87aa-411f-9eff-2546c03f2398" />

(Add screenshot here)

### Questions

1.  Who owns the file? team 19
2.  What are the default permissions?

### Reflection

Why is file ownership important in Linux systems?

------------------------------------------------------------------------

## Task 2 --- Restrict File Permissions

Run:

    chmod 600 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)

### Questions

1.  Who can read the file now?
2.  Who cannot access it?


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)

### Questions

1.  Who can access the file now?
2.  Why might this configuration be dangerous?

