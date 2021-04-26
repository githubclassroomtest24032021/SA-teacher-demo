# Demo Mission
This is a demo Mission Repository for Source Academy. This file should document the correct format for all Mission Repositories and also their intended usage with GitHub Classrooms and the Source Academy website.

If you would like to create your own mission repository, make sure to name the repository with the `SA-` prefix.

## Repository Contents
Each mission repository should contain the following:
- a `README.md` file: This functions as the Mission Briefing for the entire mission. It should give students a primer as to the entire assignment.
- a `METADATA` file: This carries important Metadata.
- Question folders: Each of these correspond to a single question.

The sections below will specify the necessary components for each mission repository.

### Readme
The Readme file is what you are currently reading!

It should give a brief overview of what to expect in the question, or otherwise guide your students along.

### Metadata
The `METADATA` file carries some important information about the mission. Each property in the `METADATA` file should be kept to one line and use the following format:
```
propertyName=value
```
The property names should be written in `camelCase`.

The following properties should be included in the `METADATA` file:
| Property      | Value | 
|:--------------|:------|
|`title`        |The display title of the Mission. This is typically different from the repository name.|
|`webSummary`   |A one-line summary of the Mission.|
|`coverImage`   |A link to the Mission's image.|
|`sourceVersion`|The version of Source the compiler will use. Should be 1, 2, 3 or 4.|

 
### Question Folders
Each question folder corresponds to a single problem/task/question in the mission. They should be named `Q1`, `Q2`, `Q3` and so on.

Each folder should contain another 2 files, `Problem.md` and `StarterCode.js`:
- `Problem.md` should contain the description of the question that the student needs to solve. This should be written in Markdown. 
- `StarterCode.js` should contain the template code for the question.

## Testing Your Repository
### Authorizing our application for your Classroom
Source Academy might not be able to see your mission if it is not given permission to access your Classroom's repositories. Please follow the steps below to set the permissions:
1. Log in with GitHub through our website. By approving Source Academy, you add it to your list of personally approved apps. ![Login 1](https://user-images.githubusercontent.com/47176493/116039417-4acda700-a69d-11eb-913a-f46b4db030f9.png)
![Login 2](https://user-images.githubusercontent.com/47176493/116039529-6df85680-a69d-11eb-923b-aadd689ac294.png)

2. On your account, navigate to Settings > Applications > Authorized OAuth Apps. 
3. Click on the Source Academy app, then grant permission for your classroom application.
![Organization access](https://user-images.githubusercontent.com/47176493/116039582-7d779f80-a69d-11eb-9c10-a7e2b201c96f.png)

### Opening your Mission
If you would like to view your repository from the student's perspective, please follow the following steps:
1. Go to the `Mission Editor` mode on Source Academy.
2. Log-in with GitHub, and click on the `My Missions`.
3. Find the Mission that you would like to view and click on `Open`. ![Mission Browser](https://user-images.githubusercontent.com/47176493/116039682-9ed88b80-a69d-11eb-86c7-40224b54cd86.png)

4. You should be able to navigate between different questions and read the Problem descriptions and the Mission Briefing.  ![Loaded Mission](https://user-images.githubusercontent.com/47176493/116039758-b6177900-a69d-11eb-8924-20c159b3bbf0.png)


### Saving your changes
1. Make changes to the code files through the editor.
2. Click on the `Save` button. A prompt will appear. Click `Confirm` to proceed.
3. If nothing goes wrong, your changes will be saved back to the repository. ![Forced Save](https://user-images.githubusercontent.com/47176493/116039803-c3ccfe80-a69d-11eb-8997-ad55cc0d61d9.png)


## Sharing Your Repository
Mission Repositories are intended to be used with GitHub classrooms. This section is a guide showing how they should be used:

1. [Clone](https://github.com/githubclassroomtest24032021/SA-mission-example) or create a Mission Repository. Then, set it as a template.
![Set Template](https://user-images.githubusercontent.com/47176493/116039861-d9dabf00-a69d-11eb-8d91-df54974b305d.png)
2. Navigate to the [GitHub Classroom](https://classroom.github.com/) page for your classroom.
3. Create a new assignment, setting the prefix to begin with `SA-`.
![Set prefix to start with SA-](https://cdn.discordapp.com/attachments/811062470571589703/836120038783057940/unknown.png)
4. Use the Mission Repository as the template for the new assignment.
![Use the template repository as the template](https://cdn.discordapp.com/attachments/811062470571589703/836120271810592768/unknown.png)
5. Obtain the link for the assignment and share it with your students.![Get the Assignment Link](https://cdn.discordapp.com/attachments/811062470571589703/836120481165213706/unknown.png)
6. Accepting the assignment should clone the repository into their account.
7. Now, they may navigate to the Source Academy website, open the Mission and edit its contents from there.
