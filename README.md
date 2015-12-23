** The current .gitignore file content is just like below, and you can add this repo as a upstream **
	
	## .gitignore for Grails 1.2 and 1.3

	# .gitignore for maven 
	target/
	*.releaseBackup

	# web application files
	#/web-app/WEB-INF
 
	# IDE support files
	/.classpath
	/.launch
	/.project
	/.settings
	/*.launch
	/*.tmproj
	/ivy*
	/eclipse
 
	# default HSQL database files for production mode
	/prodDb.*
 
	# general HSQL database files
	*Db.properties
	*Db.script
 
	# logs
	/stacktrace.log
	/test/reports
	/logs
	*.log
	*.log.*
 
	# project release file
	/*.war
 
	# plugin release file
	/*.zip
	/*.zip.sha1
	 
	# older plugin install locations
	/plugins
	/web-app/plugins
	/web-app/WEB-INF/classes
	 
	# "temporary" build files
	target/
	out/
	build/
	 
	# other
	*.iws
	 
	#.gitignore for java
	*.class
	 
	# Package Files #
	*.jar
	*.war
	*.ear
	 
	## .gitignore for eclipse
	 
	*.pydevproject
	.project
	.metadata
	bin/**
	tmp/**
	tmp/**/*
	*.tmp
	*.bak
	*.swp
	*~.nib
	local.properties
	.classpath
	.settings/
	.loadpath
	 
	# External tool builders
	.externalToolBuilders/
	 
	# Locally stored "Eclipse launch configurations"
	*.launch
	 
	# CDT-specific
	.cproject
	 
	# PDT-specific
	.buildpath
	 
	## .gitignore for intellij
	 
	*.iml
	*.ipr
	*.iws
	.idea/
	 
	## .gitignore for linux
	.*
	!.gitignore
	!.gitattributes
	!.editorconfig
	!.eslintrc
	!.travis.yml
	*~
	 
	## .gitignore for windows
	 
	# Windows image file caches
	Thumbs.db
	ehthumbs.db
	 
	# Folder config file
	Desktop.ini
	 
	# Recycle Bin used on file shares
	$RECYCLE.BIN/
	 
	## .gitignore for mac os x
	 
	.DS_Store
	.AppleDouble
	.LSOverride
	Icon
	 
	 
	# Thumbnails
	._*
	 
	# Files that might appear on external disk
	.Spotlight-V100
	.Trashes
	
	## hack for graddle wrapper
	!wrapper/*.jar
	!**/wrapper/*.jar
