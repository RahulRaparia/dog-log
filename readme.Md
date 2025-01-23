# dog-log

This is a data collection app for generating big data of dogs and their characteristics for identifying a dog from just an image and get its data.   


curl -s "https://get.sdkman.io" 
bash source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk install gradle


mkdir data-collection-app
cd data-collection-app
gradle init --type spring-boot --dsl groovy --test-framework junit --project-name auth-service --package com.doglog.authservice

# Data Collection Service
gradle init --type spring-boot --dsl groovy --test-framework junit --project-name data-collection-service --package com.doglog.datacollection