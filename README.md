## git commit -m vs git commit -a -m

The `git commit -m` command commits only the changes that have already been added to the staging area using `git add`. `git commit -a -m` automatically stages and commits changes to files that are already tracked by Git, so `git add` is not required for those files. But `-a` does not include new untracked files, which must still be added using `git add` before committing.

<img width="1247" height="107" alt="Screenshot 2026-09-04 210653" src="https://github.com/user-attachments/assets/f44b9b6b-e991-4c5f-bebd-c0bdecd72519" />
<img width="1278" height="442" alt="Screenshot 2026-09-04 210721" src="https://github.com/user-attachments/assets/19c0396d-aed1-422f-8984-fa059f6dff84" />
<img width="1337" height="231" alt="Screenshot 2026-09-04 210727" src="https://github.com/user-attachments/assets/4a098fed-ba04-40ab-a4db-e6295ce9403e" />

## Git Cherry-Pick

The `git cherry-pick` command is used to apply the changes from a specific commit to the current branch without merging the entire branch. First, the required commit is identified using `git log --oneline`, then `git switch` is used to move to the target branch, and `git cherry-pick <commit-id>` applies the selected commit. If a conflict occurs, the conflicting files must be resolved, staged using `git add`, and the operation completed with `git cherry-pick --continue`.

<img width="1406" height="616" alt="image" src="https://github.com/user-attachments/assets/af540721-c43c-4178-9ef1-47bafad02e46" />

<img width="1370" height="710" alt="image" src="https://github.com/user-attachments/assets/de50f6c5-fe23-4bd0-ab93-89c7d6e24dd8" />

<img width="1287" height="672" alt="image" src="https://github.com/user-attachments/assets/250eb4bb-69ea-47ad-98ac-262394499cab" />

<img width="1282" height="612" alt="image" src="https://github.com/user-attachments/assets/66c851d7-a990-4835-9428-3be7ccd718eb" />
