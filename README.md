# incredible
A tool for cycling AWS access keys in IAM and in your AWS shared credentials file

# Braindump features
- Take a `--profile` flag to specify which profile to use and replace for
- A verbose mode that will print the new keys to stdout (default should be to quietly generate new keys and update configuration
- Option to write existing keys to something like ssm secrets manager before replacing them in the event of failure
