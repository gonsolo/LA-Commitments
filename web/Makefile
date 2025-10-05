view:
	hugo server
deploy:
	hugo --gc --minify
	scp -r public/* stefaniereiter.de@ssh.strato.de:LA-Commitments
.PHONY: deploy view
