.PHONY : deploy local clean new

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

clean:
	@hexo clean
