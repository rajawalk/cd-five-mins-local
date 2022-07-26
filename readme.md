<h1> Instructions ~ </h1> 

To use this repository, fork it into your own account and give it a custom name. 

Use the update-git-info-*.sh script to easily update the place holders with your correct git information. (Git user, Name of forked repo)

The script will also update your application with the name of your cluster on which you wish to deploy applications. The name entered for the destination cluster should match the name of the cluster context. (The name returned by the following command)

`$ kubectl config get-contexts -o name`

***

<h3> EXAMPLE ~ </h3> 

	git clone git@github.com:nightmar39/cd-five-mins-testing.git

	cd cd-five-mins-testing

	./push/update-git-info-mac.sh 


