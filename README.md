# Taiga CLI.
Uses a mixture of Ruby and Bash.

Just basic indexing is all I got so far. 

## Commands
```bash
$ tg <us|userstory|userstories> # List all userstories in project.
$ tg <task|tasks> <-r ref#|> # List all tasks in project or by userstory ref.
```

## Setup

You'll need to set some environment variables. 

```bash
export TAIGA_USERNAME=thats-you
export TAIGA_PASSWORD=abracabra
export TAIGA_PROJECT_SLUG=my-project
```
