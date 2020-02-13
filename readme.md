_Q1: Why are readme's in github in the .md format? What is .md and why does github use it instead of .txt, .html .docx, or any other file format?_

> Readme's in github are .md or "Markdown" format. This file type is preferred for its ability to generate HTML summaries at the bottom of projects. Markdown are text files created with the markdown language style and contains inline text support.

_Q2: Is the keyword "fixes" the only way to auto-close an issue from a PR (pull request). Is there other keywords that can accomplish the same thing?_

> No, you can link a pull request to an issue with any of the keywords below:

- close
- closes
- closed
- fix
- fixes
- fixed
- resolve
- resolves
- resolved

_Q3: Do you have to create a new PR EVERYTIME you want to close an issue, or is it possible to close multiple issues within a single PR? If so, how?_

> No, you can close multiple issues with a pull request by using multiple keywords and linking them to an issue.

> For example: Resolves #10, resolves #123, resolves octo-org/octo-repo#100
