.PHONY : deploy local clean new update_fluid

local: clean
	@echo "Starting local server"
	@hexo generate
	@hexo server

deploy: clean
	@echo "Deploying to github pages"
	@hexo generate
	@hexo deploy

new:
	@echo "Creating new post $(title)"
	@hexo new post $(title)

update_fluid:
	@npm update --save hexo-theme-fluid

clean:
	@hexo clean
