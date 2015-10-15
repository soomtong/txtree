# txtree chrome app

chrome client for txtree service (with haroo cloud core)

inspirited by [GoogleChrome Text App](https://github.com/GoogleChrome/text-app)

## development

### assist in webstorm

use code reference from 

    Preference > language & framework javascript > library > download from typescript community
    
    - chrome
    - polymer

### vulcanize and crisper

every chrome app passing csp exception

    vulcanize index.html --inline-script | crisper --html build.html --js build.js

## use in chrome

go `chrome://extensions` and run load unpacked extension, select folder.

## todo

- [x] load list from local storage
- [x] save to local storage
- [ ] delete from local storage
- [ ] switch to chrome storage
- [ ] load list from cloud
- [ ] patch list from cloud by pagination
- [ ] load today list from cloud
- [ ] share to cloud
- [ ] clone from cloud
- [ ] favorite in cloud from local storage
- [ ] search in cloud
- [ ] app theme