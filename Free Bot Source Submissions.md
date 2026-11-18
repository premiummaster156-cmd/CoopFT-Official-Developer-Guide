# Free Bot Source Submissions

This public source-release workflow is separate from private commissioned bot requests.

## Developer submission
Use `/free-bot-submit` with:
- Release title.
- Description between 40 and 1,500 characters.
- Promotional image up to 8 MB.
- Exactly one source option: ZIP up to 20 MB, or the main page URL of an active public GitHub repository.

For GitHub submissions, the bot downloads the repository's default-branch ZIP. Private repositories, non-GitHub URLs, and file/folder/branch subpages are not accepted. The combined source and image upload must fit within 25 MB.

## Review
The bot sends the source ZIP, image, and description to the configured owner for private Approve/Reject review. Approval publishes the release in the configured `#free-bot-releases` channel and pings the opt-in Free Bot Releases role. Rejection sends the Developer a private notice.

## Quality and safety
Submit only code you are allowed to distribute. Remove tokens, passwords, API keys, personal data, and private customer material. Describe requirements and known limitations honestly.

A public source release is not a commissioned bot built for an individual member and does not create a customer ticket.
