.PHONY : deploy local clean
deploy: clean
	@echo "Deploying to github pages"
	@hexo generate
	@hexo deploy

local: clean
	@echo "Starting local server"
	@hexo generate
	@hexo server

clean:
	@hexo clean
