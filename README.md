<<<<<<< HEAD
# Systems for Machine Learning Induction Assignment 2025


## Disclaimer

This assignment may initially seem very daunting and complex. However, it is designed to be completed step-by-step, and each task is independent of one another. Remember, the goal is also to learn and grow your skills, so don't hesitate to ask for help when needed!

It will likely not be possible to complete the entire assignment in one seating. It is recommended to break it down into smaller tasks and tackle them one at a time.

Even if you are not able to complete the assignment in its entirety, please make a submission. We'd love to see how much progress you were able to make, and it is the effort that counts!

![Meme: we know this is way too steep of learning curve](assets/intro.png)


## Overview

The assignment is divided into three main tasks:
- **Task 1: Paper Reading: Attention is All You Need**
- **Task 2: Implementing FedAvg (a Federated Learning Algorithm)**
- **Task 3: Understanding about Quantization - a method to improve model performance**


Just reading these you may feel that they are a bunch of buzz-words, but don't worry! We will test you on how well you were able to navigate being thrown into the deep end of the pool :)

We will start from simple understanding of the working of modern large language models (like ChatGPT) in Task 1. 

For Task 2, we will take a detour to learn a little about Federated Learning and getting hands dirty with Pytorch. Federated Learning is a method to train machine learning models on data that is distributed across multiple devices, without the need to centralize the data. Essentially it means I can train a machine learning model without actually looking at the data. This is particularly useful for privacy-sensitive applications.

Finally in Task 3, we will learn about how to run these Large Langauge Models on small devices like your laptop or a mobile phone using Quantization.

Quantization is a technique that reduces the precision of the numbers used to represent model parameters, which can significantly decrease the model size and improve inference speed without a substantial loss in accuracy. This is particularly important for deploying models on edge devices with limited computational resources.

## Repository Structure

The repository is structured with each task contained within its own directory. The instructions and the task details are provided in the respective README.md files within each task directory.


## Instructions to Submit

Please clone this repository and complete the tasks in your copy of the repository. Once you have completed the tasks, you can push the changes to a **private** GitHub repository and add the following GitHub users as [collaborators](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/repository-access-and-collaboration/inviting-collaborators-to-a-personal-repository) to your repository:
- vimarsh244
- pranav-m-r
- sohlost


## Any Questions?

Please feel free to reach out to any of us over Slack or email if you have any questions or need any clarifications regarding the assignment.

- Vimarsh Shah
- Atharva Pandit
- Pranav M R
- Soham Dambalkar


Again, it is completely fine if you are not able to complete the entire assignment. Please do make a submission with whatever you were able to complete. Good luck and happy learning!
=======
# DaSH Lab Induction Assignment | 2025

## Disclaimer
This assignment might initially seem daunting, but please try not to be discouraged by the learning curve. Being research-oriented, it is designed to be challenging and time-consuming, with some open-ended elements. It will likely not be possible to complete in a single sitting, so please plan accordingly.

If you're a first or second year student attempting this assignment, be prepared to be exposed to some unfamiliar concepts, terminology and tools. Take things slow, and try to understand the fundamentals; we value depth a lot more than breadth.

If you have some prior experience, you might want to devote more time to the open-ended parts. These sections are more exploratory, and push you to apply existing ideas creatively to solve more practical problems.

Even if you are not able to complete the assignment in its entirety, please make a submission. We'd love to see how much progress you were able to make. An incomplete assignment doesn't equal an automatic rejection.

## General Instructions
The assignment has three independent buckets/paths which you can choose from:
- Distributed Systems (branch: `distributed-systems`)
- Machine Learning for Systems / Systems for Machine Learning (branch: `ML-sys`)
- Systems (branch: `systems`)

You are required to pick <u>**ONLY ONE**</u> of these.

We discourage attempting more than one bucket, especially for first year students. Completing a single bucket thoroughly should occupy most of your time. Reiterating: we value depth over breadth; we would rather have you dive deep into the open-ended section of one bucket rather than spend time on more than one of them. Owing to the open-ended nature of research, your work on the open-ended portions will be the best indicator of your understanding and skills.

You can find further instructions for each bucket in the respective branch (listed above) of this repository. You may clone the appropriate branch, and start working from there.

### Repository Setup Instructions
- First, clone the chosen branch of our public repository:
    ```
    git clone --branch <branch-name> --single-branch https://github.com/DaSH-Lab-CSIS/DaSH-Lab-Induction-Assignment-2025.git
    ```
- Remove the public repository as the remote:
    ```
    cd DaSH-Lab-Induction-Assignment-2025
    git remote remove origin
    ```
- Create a new <u>**PRIVATE**</u> repository linked to your own GitHub account.
- Add this new repository as the remote:
    ```
    git remote add origin https://github.com/<your-username>/<your-repo-name>.git
    ```
- Push your modified files to this repository:
    ```
    git push -u origin <branch-name>
    ```
- When you're ready to submit, add the following account as a collaborator with the 'write' role (<u>**DO NOT FORGET THIS STEP**</u>):
    - GitHub Username: `dash-recruiter`
    - Profile Link: `https://github.com/dash-recruiter`

## Support
Please join our [Slack workspace](https://join.slack.com/t/dashlaboutreach/shared_invite/zt-3hj00s42o-8tbKFpKVO7mP7tEIkyLK~w) to keep up with announcements related to the induction process, and also to ask questions / ask for help if you're stuck.

## LLM Usage Policy
You are free to use your favourite LLMs as coding / research assistants.

We do <u>**NOT**</u> look unfavourably upon LLM generated code, as long as you understand the implementation and are able to make modifications if required.

We <u>**STRONGLY DISCOURAGE**</u> pasting the entire problem statement into an LLM and submitting the output without any modifications. The assignment is meant to test your understanding and ability to tackle novel problems. As such, you should be able to *explain* in your interview the content you have studied and the solution you have implemented.

## Submission Deadlines
- First Deadline:
    - Friday, 7th November 2025, 11:59 PM
    - [GForm for First Deadline](https://forms.gle/2NXegrTQy6DxXWrH6)
- Second Deadline:
    - Tuesday, 11th November 2025, 11:59 PM
    - [GForm for Second Deadline](https://forms.gle/cEMRr7m82zNtR1Gu9)

You are <u>**NOT**</u> expected to have completed all the work by the first deadline. It is meant to serve as a progress update, but submission is still mandatory.

If you do complete the assignment by the first deadline, you need not make the second submission.
>>>>>>> 44ca7b032ecfa80eb87eb58829e1d4b8593aeb80
