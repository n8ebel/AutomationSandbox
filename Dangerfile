message "Thanks @#{github.pr_author} 👍👍"

# Make it more obvious that a PR is a work in progress and shouldn't be merged yet
warn("PR is a Work in Progress and not ready to merge") if github.pr_title.include? "[WIP]"
