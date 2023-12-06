# Learning Static Code Analysis
This is the repository for the LinkedIn Learning course Learning Static Code Analysis. The full course is available from [LinkedIn Learning][URL-lil-course].

![Learning Static Code Analysis][URL-lil-thumbnail]

If you’re just getting started in your career or are interested in landing a new role in DevSecOps, you may want to consider boosting your skills in static code analysis. In this course, explore the tangible benefits of DevSecOps, particularly static code analysis, along with some of the common tools and techniques used frequently in Azure to perform it. Instructor Kalyna Reda provides hands-on, interactive demonstrations that show you how to scan open-source code, set up and scan a YAML pipeline, publish the results of a scan, and improve your code based on a scan’s findings. By the end of this course, you’ll be prepared to take your new skills to the next level with additional deployments and other cutting-edge DevSecOps tools.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout: [Files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:

 - Add changes to git using this command: `git add .`
 - Commit changes using this command: `git commit -m "some message"`


### Instructor
Kalyna Reda


Check out my other courses on [LinkedIn Learning][URL-instructor-home].

[URL-lil-course]: https://www.linkedin.com/learning/learning-static-code-analysis
[URL-lil-thumbnail]: https://media.licdn.com/dms/image/D560DAQEBGmKyPRvRpQ/learning-public-crop_675_1200/0/1700085516068?e=2147483647&v=beta&t=wf5hfcE9ubG4YEFErlqdy_I3bff605Whw42EEnxkbe4
[URL-instructor-home]: https://www.linkedin.com/learning/instructors/kalyna-reda
