# README

## Usage

For instructions on setting up and using the LEDA platform, refer to the [LEDA documentation](https://solid-bassoon-28091353.pages.github.io/site/)

### Installation

To access the repo via the CMA’s LEDA platform, enter these in the terminal: 
- $ git clone git@github.com:mariapriestleycma/agents.git
- $ pip install uv &emsp;(to install required packages)
- $ uv sync


### Making and saving changes

To access modify the repo via the CMA’s LEDA platform, enter these in the terminal: 

- $ git checkout -b my_branch &emsp;(to create a new branch) 
- $ git checkout my_branch &emsp;&emsp;(to checkout an existing branch) 
- $ git merge master (to merge changes on the master branch)

To save changes to the repo:

- $ git add xxx.py &emsp;&emsp; &emsp;&emsp;&emsp;&emsp;&emsp;(to stage for commit)
- $ git commit -m 'comment 2' &emsp;(to commit changes)
- $ git push origin my_branch &emsp;&emsp;(to push update on GitHub)

Other useful commands:

- $ git branch –a &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;(lists all branches)
- $ git branch –r	&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;(to see remote branches) 
- $ git status
- $ git log
