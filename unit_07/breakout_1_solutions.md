# Breakout Exercise 1

Goal: Create a git repository, start tracking files and checkout an earlier commit.

# Intro (as a group)

1. Make a directory called "my-repo"
    `mkdir my-repo`
2. Initialize this directory as a git repository:
    `cd my-repo`
    `git init .`
3. Make a file in this directory called "lunch.txt"
    `touch lunch.txt`
4. Aside: lets look at what files are being tracked
    `git status`
5. Add the blank file to tracking using:
    `git add lunch.txt`
6. Make your first commit by running the command:
     `git commit -m "Initial Commit"`
7. We made our first commit! Let's look at our commits:
     `git log`


# Breakout 1 (groups of 2)

6. Modify lunch.txt. 
Use Vim to write what Parter A had for lunch today inside the lunch.txt file
    `vim lunch.txt`
    `i` enter insert mode 
    type and add the text you want to
    `esc` leave editing mode
    `:w` write your changes to the file
    `:q` quit Vim
We can also do this with echo and pipe commands we learned about yesterday.
    `echo "burrito" > lunch.txt`
7. Check git status - does git think things changed? 
    `git status`
8. Make a second commit with the new change.
    `git commit -m "Add PartnerA lunch`
9. Modify lunch.txt again to add what Partner B had for lunch today on another line.
    `echo "PB&J" >> lunch.txt`
10. See what changes have been made since your last commit
    `git diff`
11. Commit Again
    `git commit -m "Add PartnerB lunch`


# Breakout 2 (groups of 2)

1. Make a new file dinner.txt with both partners dinner plans for tonight in it.
    `echo "burger" >> dinner.txt`
    `echo "pho" >> dinner.txt`
2. Use vim to modify what Partner B had for lunch in lunch.txt. Change the file to say their favorite lunch, rather than what they had today.
    `vim lunch.txt`
3. Add all files to staging area.
    `git add -A`
4. Make a new commit with the changes
    `git commit -m `
5. Checkout an earlier version of the lunch file

# Merging / Branching (groups of 3)


