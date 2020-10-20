# susecloud-repocheck
SUSECloud Update Infrastructure Check for Azure, AWS, GCP

Two requirements:
1. Run as root
2. Only run on an instance that has repository issue (why else would you)

You can run it most easily with this if you have port 443 outbound opened on the instance:  
bash <(curl -sL https://github.com/rfparedes/susecloud-repocheck/releases/download/1.0.0/sc-repocheck.sh)

You can also download directly from github

![](sc-repo.gif)
