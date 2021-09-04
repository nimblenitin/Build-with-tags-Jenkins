# Build-with-tags-Jenkins

Steps to configure a build job in Jenkins to build from a Git tag-

```

1. Install the Git parameter plugin under manage Jenkins.

2. Create a tag in Git. The below repo. has a git tag-
https://github.com/nimblenitin/Parameterized-builds-Jenkins.git 

3. Create a freestyle job in Jenkins.
- In the option, select parameterized build with option of Git parameter.
- Add the SCM as Git with URL of tagged repo.
- In the Branches to Build field, enter the variable name as, ${tag}

4. Build the Job.
- Build with parameter and view the console output

```
