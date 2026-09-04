The `git commit -m` command commits only the changes that have already been added to the staging area using `git add`. `git commit -a -m` automatically stages and commits changes to files that are already tracked by Git, so `git add` is not required for those files. But `-a` does not include new untracked files, which must still be added using `git add` before committing.

<img width="1247" height="107" alt="Screenshot 2026-09-04 210653" src="https://github.com/user-attachments/assets/f44b9b6b-e991-4c5f-bebd-c0bdecd72519" />
<img width="1278" height="442" alt="Screenshot 2026-09-04 210721" src="https://github.com/user-attachments/assets/19c0396d-aed1-422f-8984-fa059f6dff84" />
<img width="1337" height="231" alt="Screenshot 2026-09-04 210727" src="https://github.com/user-attachments/assets/4a098fed-ba04-40ab-a4db-e6295ce9403e" />
