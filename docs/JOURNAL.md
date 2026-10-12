fifa2@PC-PORTABLE-SLIM:~/epf-cicd$ git commit --allow-empty -m "test: push direct"
[main fc64ed3] test: push direct
fifa2@PC-PORTABLE-SLIM:~/epf-cicd$ git push
Enter passphrase for key '/home/fifa2/.ssh/id_ed25519':
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 190 bytes | 190.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: error: GH006: Protected branch update failed for refs/heads/main.
remote:
remote: - Changes must be made through a pull request.
To github.com:Berkaniii/epf-cicd.git
 ! [remote rejected] main -> main (protected branch hook declined)
error: failed to push some refs to 'github.com:Berkaniii/epf-cicd.git'
fifa2@PC-PORTABLE-SLIM:~/epf-cicd$ git reset --hard origin/main
HEAD is now at 3d2505d ci: mise à jour des actions