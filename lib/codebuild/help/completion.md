Example:

    codebuild completion

Prints words for TAB auto-completion.

Examples:

    codebuild completion
    codebuild completion hello
    codebuild completion hello name

To enable, TAB auto-completion add the following to your profile:

    eval $(codebuild completion_script)

Auto-completion example usage:

    codebuild [TAB]
    codebuild hello [TAB]
    codebuild hello name [TAB]
    codebuild hello name --[TAB]