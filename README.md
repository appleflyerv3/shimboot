script has been forked from ading2210/shimboot so that images can be built on github without the need for a linux computer
MAKE SURE YOUR BOARD IS ON dl.darkn.bio/SH1mmer, or else THIS WILL NOT WORK AT ALL

# how to use :P
1. fork this repo
2. change {your_github_username} to ur github username and go to
https://github.com/{your_github_username}/shimboot/actions
3. enable workflows on your forked repository
4. enter into the .github/workflows directory
5. open build-image.yaml
6. go to line 12, and put your board:
for example if your board is orco:

change line 12 to

`12  board: [orco]`

7. then, click commit changes
8. change {your_github_username} to ur github username and go to
https://github.com/{your_github_username}/shimboot/actions/workflows/build-image.yaml
9. once the workflow is done, download ur shit.

how to use shimboot instructions, if it wasnt clear enough in the original shimboot github README is here
<https://www.reddit.com/r/SGExams/comments/1chkvv9/how_to_unenrollkinda_a_chromebook_part_2_yes_this/>
