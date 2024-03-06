# clone-all_repos_github

 gh repo list <org_name or username> --json name --jq '.[].name' | while IFS= read -r repo; do gh repo clone "<org_name>/$repo"; done
