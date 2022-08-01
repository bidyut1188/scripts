Work with GitHub repositories.

## USAGE
  gh repo <command> [flags]

## CORE COMMANDS
  - archive:     Archive a repository
  - clone:       Clone a repository locally
  - create:      Create a new repository
  - delete:      Delete a repository
  - deploy-key:  Manage deploy keys in a repository
  - edit:        Edit repository settings
  - fork:        Create a fork of a repository
  - list:        List repositories owned by user or organization
  - rename:      Rename a repository
  - sync:        Sync a repository
  - view:        View a repository

## INHERITED FLAGS
  --help   Show help for command

## ARGUMENTS
  - A repository can be supplied as an argument in any of the following formats:
  - - "OWNER/REPO"
  - - by URL, e.g. "https://github.com/OWNER/REPO"

## EXAMPLES
  - `$ gh repo create`
  - `$ gh repo clone cli/cli`
  - `$ gh repo view --web`

## LEARN MORE
  - Use 'gh <command> <subcommand> --help' for more information about a command.
  - Read the manual at https://cli.github.com/manual
