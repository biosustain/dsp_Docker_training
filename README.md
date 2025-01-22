# Docker introduction for Data Club 2025-02-19

What if reviewer number 2 tells you that it is impossible to reproduce your results? Oops! Figuring out all software versions and dependencies in your system and in the reviewer's system and compare them sounds like very tedious work! Wouldn't it be nice to send him/her your pipeline as a Docker image, with the needed software preinstalled and all the dependencies in place?

If you built a workflow for your analysis that uses different bioinformatics tools, each of these tools may have specific version requirements. By creating a Docker image with all these tools preinstalled, you can ensure that your pipeline runs in any machine (laptop, HPC or cloud). You can also share this image with your collaborators, or reviewer number 2, to ensure reproducibility of the results. Furthermore, your pipeline can more easily be deployed on the cloud.

Docker improves bioinformatics workflows by ensuring reproducibility and portability, which makes it essential in computational biology.

In this course Docker will be introduced and a practical example will be shown to you. In more detail the course will cover the following:
- What is Docker and why is needed?

- How to install it - Requirements, best practices.

- Run, pull or login interactively in your container.

- Creating your first Dockerfile and adding some software (rnaseq realeted).

- File system mounts.

- Uploading the container image in Docker hub.