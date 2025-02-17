# AcreetionOS_Package_Request_Repo
Are you wanting to request a package? Do it according to the following scheme: 
```
1) Get tne request for the package as an issue on the *AcreetionOS Package Request Repo*
		a. Setup folders in repo as following:
				1. Request
				2. PKGBUILD
				3. FINISH_PKGBUILD
		b. Have automated Chron Job Clone/Pull AcreetionOS Package Request Repo and move everything within FINISH_PKGBUILD to Liv REPO
		c. Liv/other member verifies package working
		d. Signs off on package
		
	2) Discuss with individual about specific implementation
		a. Place as folder inside Request folder on AcreetionOS Package Request Repo
	3) Check AUR for package build
		a. Build PKGBUILD if not found
	4) Place PKGBUILD in PKGBUILD/ Folder
	5) Have someone proof read the PKGBUILD and sign-off
	6) Place PKGBUILD in FINISH_PKGBUILD
		a. PKGBUILD Copies as referenced in 1)
	7)PKGBUILDs get pushed to Testing
	8)PKGBUILDs get pushed to Main after Johnathan/Darren finish testing


```

AcreetionOS Repo for Requesting Packages
