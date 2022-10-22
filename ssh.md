Using GitHub through SSH

1. Check if you have an SSH key already:
	cat ~/.ssh/id_rsa.pub
2. If you don't have one, create a new one (empty passphrase):
	ssh-keygen -t rsa -f ~/.ssh/id_rsa
3. Go to GitHub and add the key under settings > SSH and GPG keys
4. Test your connection:
	ssh -T git@github.com
