.PHONY : deploy local
deploy:
	@echo "Deploying to $(DEPLOY_TARGET)"
	@hexo clean
	@hexo generate
	@hexo deploy

local:
	@echo "Starting local server"
	@hexo clean
	@hexo generate
	@hexo server
