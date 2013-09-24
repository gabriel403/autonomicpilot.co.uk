#CV

#Contact Details

<table style='width: 100%'>
	<tbody>
		<tr>
			<td>Gabriel Baker</td>
			<td>gabriel@autonomicpilot.co.uk</td>
			<td>129 Barclay St</td>
		</tr>
		<tr>
			<td>&nbsp;</td>
			<td>+44 7894 387832</td>
			<td>LE3 0JE</td>
		</tr>
	</tbody>
</table>

#Personal Statment

I am an open source software architect, specializing in PHP.

I am currently project lead for various projects at GoMAD Technology, the technology arm of GoMAD Thinking, including the administrative website for iCheev.

I'm a passionate open source advocate producing various modules to ease the use of Zend Framework 2, as well as my own website/blog, making use of various open source tools, such as Michelf's PHP Markdown Extra and GitHub for hosting. I blog on various PHP/JS related topics and present talks on various subjects.

#Work Experience

##Placement Year

During my placement year at university I started as a junior web developer working for Go MAD Thinking, working on iCheev, I quickly became the server administrator handling SVN, access control, testing and live servers as well as deployment.

I also introduced the trac bug tracking system which we've used to track the development process of new features as well tracking bugs from discovery to fixed.

##Post Graduate

After graduating I went back to working for the same company as web developer/server administrator.
I started working with more languages such as C#.NET and ruby.

####Jenkins CI

I also worked to integrate our provisional suite of unit tests into a more continuous solution by the introduction of Jenkins CI to routinely run our increasing suite of unit tests. I then progressed to using Jenkins CI to automate our deployment through the testing stages and finally to the live deploy.

####Git

As a frequent contributor to open source projects, most of them through github I introduced the company to git and championed the use of git as our vcs, finalising with a [presentation](http://slid.es/gabriel403/git-githubgitlab-gitflow/) on git, github and gitflow to the majority of the company upon which the decision was taken to move forward with git. We are now in transition from subversion to git on github.

####boxen

After discovering the wonders of puppet and vagrant (and how github use puppet to set up their local dev machines (I stole the name)) and how well they could be combined I started work on a project to enable our devs to spin up vagrant instances to use as dev servers. I also produced configurable puppet scripts that would reproduce our various development projects, with all server dependencies, with minimal fuss. This allowed rapid deployment of our projects to new nodes as needed. This also freed the devs and allowed them to use any combination of operating system and hardware they wished whilst still running their development on the vagrant boxes which would replicate a common environment. Extra vagrant boxes were generated to enable developers to replicate different environments from our 'edge' development server all the way to production, all on VMs on their local machine. This also lead to new technologies being implemented as puppet scripts allowing easy deployment amongst developers and then on servers, as the puppet scripts don't need to run on a virtual. This also enabled writing puppet scripts to set up brand new or newly reinstalled machines with all the programs a dev needs.

####PHPCI

I work in my spare to help on the PHPCI project. This is a PHP based continuous integration server, with plugins for various PHP tools, such as PHPUnit, Mess Detector, Code Sniffer, PHP-CS-Fixer and lots more. It works with local and remote respositories, including building on demand and when pushes to github/gitlab happen.

