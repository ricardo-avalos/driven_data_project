# Claude Code Instructions

## Who I am
This is a solo research project. I am the only human working on this repo. It can change in the future, but I will modify this md when it occurs. 

## Git rules — CRITICAL
- NEVER push to main under any circumstances
- NEVER create a pull request to main without explicitly being asked
- Always work on the developer branch which will be called "dev"
- NEVER commit .env files or any file containing credentials
- NEVER commit raw data files (csv, dta, xlsx, parquet, rds)

## Folder structure rules
- Never modify files inside any input/ folder — these are read-only inputs
- Each folder will represent a task such as cleaning, analysis_dataset and others. 
- Always write outputs to the output/ folder of the current stage
- Code belongs in code/, configuration files belong in hand/
- Never delete files without explicitly asking me first

## DVC rules
- Data outputs are managed by DVC — run dvc push after producing new outputs
- Never manually upload data files to GitHub

## Coding style
- Use R with tidyverse for data work unless I specify otherwise
- Use Python only if I explicitly ask for it
- Comment every function explaining what it does
- Use snake_case for all variable and file names
- When producing an output, create two versions differentiated by a suffix (one having the current date as suffix and one with suffix "up_to_date")

## General behaviour
- Ask me before making structural changes to the project
- If unsure about something, stop and ask rather than guessing, unless I explecitely ask you to finish a first pass of work 
- Summarize what you did at the end of each task by printing in the terminal 
