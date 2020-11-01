Computer Class Instance macbookPro
this.operatingSystem = 'Mac Catalina'
this.hardDriveSpaceInGb = 500
this.gpu = 'intel random gpu'
this.caseType = 'laptop'
this.hasScreen = true
Methods
macbookPro.addGpu() = Would change the value of gpu to have the original string and an additional, 'random gpu 2'
macbookPro.removeGpu() = Would take away the new gpu just added to the value through .addGpu resulting in just 'intel random gpu' like the start
macbookPro.updateOs() = would reassign string of operatingSystem to a newer version, ex 'Mac Catalina 15.15.14'
macbookPro.connectMonitor() = would do nothing because the hasScreen is already true, ideally there would have been another attribute numOfScreens if so numOfScreens would increment to 2
macbookPro.installSoftware() = would decrease hardDriveSpaceInGb to whatever given argument is asking
