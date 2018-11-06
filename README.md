# Himma
Sync gitlab or local git contributions to github account

## How it works
- Create github repo named XXX to record commits   
- Every time when you do git commit, will trigger commit-msg hook   
- Add mock commit to your github repo XXX when commit-msg is triggered   
- Push mock commit automatically   

## Install
- Git clone   
  - `git clone https://github.com/KevinOfNeu/Himma.git`
  - `cd Himma`

- Edit configuration   
  Replace repo with yoursef

- Run `./configure`
  

## Config 
- Already exists repos   
  Run `git init` to copy git hooks

- New git repos   
  No futher configs

## Sync
Everytime when you commit on a configured repo, you will sync commit to github

## Privacy
Himma only record commit date and write to your github repo


