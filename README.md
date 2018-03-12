# git-stats

Jupyter notebook that demonstrates how to parse sorce code and look for certain features using GitHub API.

To get started create .env file with following content:
```
# configuration
GITHUB_USER=git_username
GITHUB_PASSWORD=git_password
```

This sample looks for files with .java extension and counts number of code lines that contain Spring Boot REST Controller (@RestController) or representing REST operation (@RequestMapping)
