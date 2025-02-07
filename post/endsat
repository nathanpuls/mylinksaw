# ends.at - Custom Redirect Service

## Overview
**ends.at** allows users to create a short, memorable URL that redirects to any link of their choice. Each user gets a unique username at the end of `ends.at/username`, which fetches a redirect link stored in their GitHub repository.

## How It Works
1. **User Setup**
   - Users must have a **GitHub account**.
   - They create a **public repository** named `endsat` under their GitHub username.
   - Inside this repository, they create a file named `endsat.txt` containing the URL they want to redirect to.

2. **Redirect Process**
   - When someone visits `ends.at/username`, the system fetches `endsat.txt` from `https://raw.githubusercontent.com/username/endsat/main/endsat.txt`.
   - The user is then automatically redirected to the URL inside `endsat.txt`.

## Setting It Up
Follow these simple steps to create your custom redirect:

### **Step 1: Create the Repository**
1. Go to [GitHub](https://github.com/new).
2. Name the repository **`endsat`**.
3. Make it **public** (so the redirect service can access it).
4. Click **Create repository**.

### **Step 2: Add the Redirect File**
1. Inside your new `endsat` repo, click **Add file → Create new file**.
2. Name the file `endsat.txt`.
3. In the content area, enter the URL you want to redirect to (e.g., `https://example.com`).
4. Click **Commit changes**.

### **Step 3: Test Your Redirect**
Go to:
```
https://ends.at/your-github-username
```
If everything is set up correctly, you will be redirected to the URL specified in `endsat.txt`.

## Why Use ends.at?
- **Easy Setup** – No backend required, just GitHub.
- **Full Control** – Change your redirect anytime by updating `endsat.txt`.
- **No Limits** – Works with any valid URL.
- **Fast** – Uses GitHub's raw file service for quick lookups.

## Troubleshooting
- **Getting a 404 error?** Make sure your repository is public and the `endsat.txt` file exists.
- **Not redirecting?** Double-check that the URL in `endsat.txt` is valid and correctly formatted.
- **Changed the URL but still seeing the old one?** GitHub caches raw files. Try appending `?timestamp=12345` to force refresh.

## Future Enhancements
- Support for custom domains.
- Optional URL shortening.
- Web interface for easier setup.

---
Created with ❤️ for simple and efficient URL redirection.
