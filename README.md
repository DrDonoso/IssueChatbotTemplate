# Issue Chatbot Template

This is a template for creating a chatbot that can be used to process issues in a GitHub repository.

It returns outputs based on the issue template headings, output will be lowercase and will have some substitutions:

- If it contains a space it will be substituted by a underscore.

``` text
### My option
my_option
```

⚠️ You should enable **Read and write permissions** in *Settings>Actions>General>Workflow permissions for this to work*.
