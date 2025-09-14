deploy:
	hugo --gc --minify
	rclone sync public/ stefaniereiter.de:/mnt/web113/e0/35/54625835/htdocs/LA-Commitments/
.PHONY: deploy
