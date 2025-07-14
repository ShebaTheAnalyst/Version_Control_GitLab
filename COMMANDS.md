-- Cloning The Repository

	git clone https://gitlab.com/your-username/your-repo-name.git
	cd your-repo-name

-- Creating & Switching to the Working Branch

	git checkout -b working

-- Modifying and Committing HTML Files (One at a Time)
	-- about.html
		git add about.html
		git commit -m "Updated about.html: Added Core Values section under About Us"

	-- services.html
		git add services.html
		git commit -m "Updated services.html: Added Cloud Integration as a new service section"

	-- team.html
		git add team.html
		git commit -m "Updated team.html: Added new team member Yara with description for Task"

-- Push Working Branch
	
	git push origin working

-- Creating Test Branch and Adding Student ID
	
	git checkout -b Test

-- Edit README.md with Student ID, then:

	git add README.md
	git commit -m "Added student ID to README.md on Test branch"
	git push origin Test

-- Merge Conflict Simulation
	
	-- Switch Back to Working Branch & Make a Conflicting Change
		git checkout working

	-- Add Git Version Number to README.md
		git add README.md
		git commit -m "Added Git version number to README.md on Working branch"

	-- Merge Test into working (Triggers Conflict)
		git merge Test

	-- After resolving the conflict in README.md:
		git add README.md
		git commit -m "Resolved merge conflict in README.md between Working and Test branches"
		git push origin working

-- git add README.md

git commit -m "Resolved merge conflict in README.md between Working and Test branches"
git push origin working

-- Tagging the Repository

git tag v1.0.0
git push origin v1.0.0

-- Creating Retrospective Folder and Files
	-- Create Folder & Files
		mkdir retrospective
		git log > retrospective/log.txt

	-- After adding summary.txt and your PDF:
		git add retrospective/
		git commit -m "Added retrospective folder with log, summary, and screenshots for D197 Step G"
		git push origin working


