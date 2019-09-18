# f19-relay

Relay programming workshop for the fall 2019 semester.

This workshop provides three (3) programming challenges which are each
aimed to be beginner-intermediate difficulty.

The workshop should take one (1) hour.

## For Participants

To get started, simply run the `setup.sh` script in this directory.

You can stop reading here and await further instructions.


## Challenge descriptions

Challenge description sources are located under the `src` directory.
PDFs are generated from RMarkdown sources via Pandoc. Markdown
compilation will require a LaTeX distribution and Pandoc to be have been
installed.

Documents are compiled as follows:

```
pandoc -o instructions.pdf instructions.md
```

## How to run this workshop

1. Instruct everyone in the workshop to split into teams of three (3)
   people.

2. Every participant should log into Github and be comfortable with
   forking and cloning projects.

3. Assign a number from 1 to 3 to each participant in each group. This
   number will correspond to the challenge that they begin with.

4. Have each participant fork this repository. Do not continue until
   everyone has done this!

5. Once everyone has a fork, ensure that each person in each team has
   exchanged their repository URLs. They should record them in a file
   like so:
   ```
   # Challenge one
   https://github.com/ParticipantOne/f19-relay.git

   # Challenge two
   https://github.com/ParticipantTwo/f19-relay.git

   # Challenge three
   https://github.com/ParticipantThree/f19-relay.git
   ```
   Each participant will begin working in their own repository, and by
   the end of the work shop, they will have worked in each of them.

6. When everyone is ready, start the timer and tell groups to open the
   `challenge_01`, `challenge_02`, or `challenge_03` folder as according
   to the number they were assigned.

   Participants will now be allowed to read their instructions and begin
   coding.

7. When time is up, yell STOP! Everyone must stop coding! They will be
   instructed to clone the next logical repository. I.e. ParticipantOne
   will clone ParticipantTwo's repo. ParticipantTwo will clone
   ParticipantThree's repo. ParticipantThree will clone ParticipantOne's
   repo.

8. Reset the timer and yell START! Participants will pick up where their
   teammate left off.

9. Repeat steps 7 and 8 one more time.

10. That's the end! Poll the room to see how people did. Did anyone
    arrive at working solutions for any of the problems? What challenges
    did people encounter? How did they get around them? Try to encourage
    some discussion.

11. Poll interest about CS Games! Now's about time to start pulling a
    team together!
