# Docker introduction for Data Club 2025-02-19

What if reviewer number 2 tells you that it is impossible to reproduce your results with the software that you described in the Methods section? Ups! Figuring out all software versions and dependencies in your machine and in the reviewer's machine and compare them sounds like very tedious work! Wouldn't it be nice to send him/her your pipeline in a Docker container with the needed software pre-installed and all the dependencies in place?

If you built a workflow for your analysis that uses different bioinformatics tools, each of these tools may have specific version requirements. By creating a Docker container with all these tools preinstalled you can ensure that your pipeline runs in any machine (laptop, HPC or cloud). You can also share this container with your collaborators or reviewer number 2 to ensure reproducibility of the results. Furthermore your pipeline can be deployed on the cloud without worrying about software installations.

Docker simplifies bioinformatics workflows by ensuring reproducibility, portability, and dependency management, which makes it essential in computational biology.

In this course Docker will be introduced and a practical example will be shown to you. In more detail the course will cover the following:
- What is Docker and why is needed?

- How to install it - Requirements, best practices.

- Run, pull or login interactively in your container.

- Creating your first Dockerfile and adding some software (rnaseq realeted).

- File system mounts.

- Uploading the container image in Docker hub.