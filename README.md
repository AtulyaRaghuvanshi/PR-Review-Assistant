Key features:
- Automatically reviews open PRs
- Leverages LLM for intelligent analysis and feedback
- Can be easily customized to fit your project needs
- Easy to set up and use

Code review flow
1. **Creating**: Authors start modifying, adding, or deleting some code; once ready, they create a change.
2. **Previewing**: Authors then use Critique to view the diff of the change and view the results of automatic code analyzers  When they are ready, authors mail the change out to one or more reviewers.
3. **Commenting**: Reviewers view the diff in the web UI, drafting comments as they go. Program analysis results, if present, are also visible to reviewers. Unresolved comments represent action items for the change author to definitely address. Resolved comments include optional or informational comments that may not require any action by a change author.
4. **Addressing Feedback**: The author now addresses comments, either by updating the change or by replying to comments. When a change has been updated, the author uploads a new snapshot. The author and reviewers can look at diffs between any pairs of snapshots to see what changed.
5. **Approving**: Once all comments have been addressed, the reviewers approve the change and mark it ‘**LGTM**’ (Looks Good To Me). To eventually commit a change, a developer typically must have approval from at least one reviewer. Usually, only one reviewer is required to satisfy the aforementioned requirements of ownership and readability.
