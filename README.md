# Autograding Example: on the teacher end

The way the auto-graded Python assignments work is the student is

1 added to the organisation providing Github education

2 given a link ie https://classroom.github.com/a/9j82gjXS.

3 They clone the assignment repo to their own computer.

4. they make provided unit tests work by fixing code, or creating code that can pass unit tests.

5. they push their code back to the remote where continuous integration runs the unit tests in the cloud (effectively objectively grading their work as a pass of all unit tests pass). I don't yet know if only most unit tests pass, if that could translate into a grade like 80%

6. If 5 yields a successful CI unit test run, a pass is visible to the advisor.


In order to make the above workflow work in a meaningful way, it would be good to have some data to work with now.

Also, I recommend that Nic and Alex do this trivial Python example. You just have to edit a string to make a unit test pass.

https://classroom.github.com/a/9j82gjXS.


# Autograding Example: on the student end
### Python
This example project is written in Python, and tested with pytest.

### The assignment
The tests are failing right now because the method isn't outputting the correct string. Fixing this up will make the tests green.

### Setup command
`sudo -H pip3 install pytest`

### Run command
`pytest`

### Notes
- pip's install path is not included in the PATH var by default, so without installing via `sudo -H`, pytest would be unaccessible.
