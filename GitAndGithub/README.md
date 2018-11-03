# GitAndGithub
![](https://imgs.xkcd.com/comics/git.png)

Geeks, First official challenge of ProjectX is going to be based on two most important things of a developer's life, `Git` and `Github`. Succesful study and completion of this challenge will give members the context of practical software development and hands on collaboration-contribution to open sourced projects.

*Challenge Date* : 28 Sept, 2018

#### What you should learn :

1. Why Git and Github Exist
2. Git Basics
3. Github ecosystem
4. Collaboration using Github

#### Challenge Format :

1. You will be given one or several repositories.
2. Long and High entropy strings(a.k.a. flags) will be hidden all over these repositories.
3. You will have to use fundamental operations and functionalities of git and github together to get these flags.
4. Different points will be awarded for different flag submissions based on difficulty.
5. Team with maximum points/(100) wins.

Example Challenge : [Link](https://github.com/CaptainFreak/GitAndGithubExample)

## *Note*: Complete the learning phase and try to get the flag yourself first !

Solution : [Link](https://gist.github.com/CaptainFreak/6d346dbef282347faf930526e3da525c)

> *For earning bonus points :)* : Each succesful PR opened by team members in time period(16-28 Sept 2018) to any open sourced project on Github will hold some bonus points for the team according to nature of project and PR.

Resources : 
1. https://services.github.com/on-demand/resources/
<br>

-----------

<strong>Challenge Link</strong> : [Repository](https://github.com/CaptainFreak/GnG-Challenge)

<strong> Editorial</strong> : 

1. Easy Peasy

You just had to look into flag.txt file in `master` branch. This challenge just aimed to get participants comfortable
with flag submissions and challenge format.

- flag : PXFlag{characters_which_will_change_you_forever}

2. Branched-Out

You just had to checkout all the branches using "git branch -a".Intended to teach to see all the branches present in the repo.

- flag : PXFlag{ElliotAlderson_Darlin_MrRobot_WhiteRose_Tyrell}

3. First Step

First commit of the repo contained a bash script which was having an instruction of executing command "curl link-to-flag(URL)".
Upon visiting the URL manually or executing the cURL command would have revealed the flag. It was meant to show you ways to
traverse to first commit and to make you aware about super useful and handy cURL cli utility.

- flag : PXFlag{Naruto_Sasuke_Itachi_Jabuza_Pain_RockLee_Obito_Minato}

4. Flames and Blames

There were two committers for challenge repository. CaptainFreak and Mr Flag with the flag as his email. You just had to check all the committers with command `git log --pretty="%an %ae%n%cn %ce" | sort | uniq` . Which includes teaching you about advance use of `git log` utility, piping in unix shell, sort and uniq commands.

- flag :  PXFlag{HarveySpectre_MikeRoss_RachelZane_LouisLitt}

5.  Morty and his wisdom

Sometimes you have to browse through commit messages to find the relevant changes in code history. Hint for this challenge was screaming loud to check commit messages. To efficiently grep to commit message you can execute `git log --all --grep="PXFlag"`.

- flag : PXFlag{RickSanchez_MortySmith_PickleRick}

6. Files-Wiles

Checking out `Feature-2` branch would have given you `image.png` which was just a text file containing flag and its extension was put `.png` to make it look corrupted when opened in standard image-viewers softwares. `cat image.png` would have revealed the flag. Supposed to teach you that files are just specification and are very easy to play with. An image can be a zip file containing rar files of other text files.(wanna know more, ping me).

- flag : PXFlag{Pablo_Havier_Mike_Tata}

7. hide and seek

`Feature-3` branch had a hidden directory which contained the flag file. Was supposed to teach you about hidden directories on unix systems. `ls -la` would have revealed the directory.

- flag : PXFlag{Kavvu_Dhruv}

8. Software Cycle

This was a the most git flavoured challenge. Wikipedia article on the provided link was hinting towards merging the branches in the sequence `pre-alpha -> alpha -> beta -> develop`. It would have revealed the flag in conflicts. This development cycle is used by many many popular open source projects, where all the initial commits from contributors goto pre-alpha branches and are merged in higher branches after thorough testing and polishing.

- flag : PXFlag{WalterWhite_Jesse_GusFring_Mike}

9. BrainFuck3r

`develop` branch had a very interesting README.md with lyrics from song `Hack All the Things - Dual Core`. Last line was containing hint about a github owner callled `BrainFuck3r`, who had only one repo with 1 PR. All things .. repo name, user name, PR comments were hinting to interprete the PR code with `BrainFucker` language interpreter. Running this code would have printed the flag. Was supposed to make you feel the level of enumeration one should do while searching for something and also the awesome esoteric language world [Link](https://esolangs.org/wiki/language_list)

- flag : PXFlag{Primer_Predestination_Trianlge_DonnieDarko_Enemy_FightClub_andManyMore}

10. The slash

This challenge went unsolved X), Even though being one of the easiest. Slash was supposed to hint at use of slash on github to activate the search bar. Searching for `PXFlag` on github  would have revealed the flag in recent indexes of code.
This challenge comes with the most useful learning of not commiting anything confidential publicly as everything in open source is indexable. People commit passwords, api keys and many other secret stuff in commit history and even big companies get breached due to developers commiting secrets to public repos.

- flag : PXFlag{APIKeys_DatabasePasswords_SSHCreds_devlopersArePussies}

11. Stargaze 

BrainFuck3rs repo had only one star. and that was from the user who had the flag in his bio. Was supposed to let you know that only interesting and followable people star interesting repositories.

- flag : PXFlag{Stalk_Fucking_Every_Stargazer_of_GoodRepos}

----------
<p align="center">
Challenge by TeamCaptainFreak
 </p>

