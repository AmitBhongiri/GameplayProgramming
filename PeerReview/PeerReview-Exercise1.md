# Code Review for Programming Exercise 1 #
## Description ##

For this assignment, you will be giving feedback on the completeness of Exercise 1.  To do so, we will be giving you a rubric to provide feedback on. For the feedback, please provide positive criticism and suggestions on how to fix segments of code.

You only need to review code modified or created by the student you are reviewing. You do not have to review the code and project files that were given out by the instructor.

Abusive or hateful language or comments will not be tolerated and will result in a grade penalty or be considered a breach of the UC Davis Code of Academic Conduct.

If there are any questions at any point, please email the TA.

## Due Date and Submission Information ##
See the official course schedule for due date.

A successful submission should consist of a copy of this markdown document template that is modified with your peer-review. The file name should be the same as in the template: PeerReview-Exercise1.md. You also need to include your name and email address in the Peer-reviewer Information section below. This review document should be placed into the base folder of the repo you are reviewing in the master branch. This branch should be on the origin of the repository you are reviewing.

If you are in the rare situation where there are two peer-reviewers on a single repository, append your UC Davis user name before the extension of your review file. An example: PeerReview-Exercise1-username.md. Both reviewers should submit their reviews in the master branch.  

## Solution Assessment ##

## Peer-reviewer Information

* *name:* Amit Bhongiri
* *email:* abhongiri@ucdavis.edu

### Description ###

For assessing the solution, you will be choosing ONE choice from: unsatisfactory, satisfactory, good, great, or perfect. Place an x character inside of the square braces next to the appropriate label.

The following are the criteria by which you should assess your peer's solution of the exercise's stages.

#### Perfect #### 
    Can't find any flaws in relation to the prompt. Perfectly satisfied all stage objectives.

#### Great ####
    Minor flaws in one or two objectives. 

#### Good #####
    Major flaw and some minor flaws.

#### Satisfactory ####
    Couple of major flaws. Heading towards solution, however did not fully realize solution.

#### Unsatisfactory ####
    Partial work, not really converging to a solution. Pervasive Major flaws. Objective largely unmet.


### Stage 1 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

#### Justification ##### 
The captain moves to the right as required. Bases the code off of the MoveCharacterLeft with the two tweaks: not flipping the sprite and making the speed positive.

### Stage 2 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

#### Justification ##### 
Each of the pirates perform the Slow, Normal, and Fast version of gathering correctly. Each performs for the correct amount of time, producing resources at the correct intervals. The resources are produced both on and near the pirate, with a tiny bit of velocity before falling to the ground and having a random range of positions to fall near the pirate. Code is logical and easy to follow.

### Stage 3 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

#### justification ##### 
Creates a random generator that generates numbers between 1 and 9, having 1-3 for slow work, 4-6 for normal work, and 7-9 for fast work. Easily understandable and is correctly implemented when the captain motivates the pirates.

### Stage 4 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

#### justification ##### 
Implemented a MoveCharacterJump that propels the Captain up and in the direction he is facing at a speed that is specified in a variable. Simple to understand.

## Code Style ##

### Description ###
Check the scripts to see if the student code follows the .Net style guide.

If there are sections that don't adhere to the style guide, please peramlink the line of code from Github and justify why the line of code has infractions of style guide.

It should look something like this:

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

Here is an example of the permalink drop down on Github.

![Permalink option](../images/permalink_example.png)

Here is another example as well.

* [I go to Github and look at the ICommand script in the ECS189L repo!](https://github.com/dr-jam/ECS189L/blob/1618376092e85ffd63d3af9d9dcc1f2078df2170/Projects/CommandPatternExample/Assets/Scripts/ICommand.cs#L5)

### Code Style Review ###

#### Style Guide Infractions ####
* Does not have an underscore in front of camelcase variables, does not matter that much though. [Here](https://github.com/ensemble-ai/exercise-1-command-pattern-yochKo/blob/72fc57227262f3e8040bfb999fc259bc2b263f93/Captain/Assets/Scripts/PirateController.cs#L32)

#### Style Guide Exemplars ####
* Has the brackets on separate lines for functions/loops. [Here](https://github.com/ensemble-ai/exercise-1-command-pattern-yochKo/blob/72fc57227262f3e8040bfb999fc259bc2b263f93/Captain/Assets/Scripts/FastWorkerPirateCommand.cs#L10)

## Best Practices ##

### Description ###

If the student has followed best practices (Unity coding conventions from the StyleGuides document) then feel free to point at these segments of code as examplars. 

If the student has breached the best practices and has done something that should be noted, please add the infracture.

This should be similar to the Code Style justification.

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

### Best Practices Review ###

#### Best Practices Infractions ####
* Does not have comments explaining what the fire2 does.

#### Best Practices Exemplars ####
* Has debug logs on the PirateController.cs that explains which numbers indicate slow, normal, and fast work. [Here](https://github.com/ensemble-ai/exercise-1-command-pattern-yochKo/blob/72fc57227262f3e8040bfb999fc259bc2b263f93/Captain/Assets/Scripts/PirateController.cs#L36)
