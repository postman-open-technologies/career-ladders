# Career Ladders we use at the OSPO (Open Source Program Office)
A snapshot of career ladders used at Postman Open Technologies and the OSPO.

## About

The Career Ladder system is a model to provide clarity to employees on what is expected and where they are in a level approach to skills and responsibilities required for a certain role. It’s about the stages of your career and how to step from one stage to the next. 

Roles up to and including Senior, ladders are constructed around becoming the best at what one does that one might personally be.

At Staff level, the career expands to help others be successful with what you do and know, and scale yourself.

At Principal and beyond, you are trying to help others be the best that they can be, removing yourself and meeting others where they are.

## Career Ladders for roles in Open Tech's Program Office
[Open Source Contributor](./career-ladder-for-open-source-contributors.md)

[OSPO Engineer](./career-ladder-for-ospo-engineer.md)

## Based upon 
[Sarah Drasner's Career Ladders](https://career-ladders.dev/)

[The Importance of Career Laddering](https://css-tricks.com/the-importance-of-career-laddering/)

[Technical Program Manager Career Path](https://www.mariogerard.com/technical-program-manager-career-path/)

[Technical Program Manager](https://www.linkedin.com/pulse/technical-program-manager-vraj-shroff/)

[Engineering Ladders](http://www.engineeringladders.com/)

[Defining a career path for Developer Relations](https://slack.engineering/defining-a-career-path-for-developer-relations/)

[What is Open Source Triage](https://osiolabs.com/blog/what-is-open-source-triage)


# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to 
greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v2
with:
  who-to-greet: 'Mona the Octocat'
