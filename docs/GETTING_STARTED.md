# Getting Started

It is very easy to get started, no environment variables or anything are required to start developing.

```bash
# Clone the repository to your own folder
git clone git@github.com:ueno-llc/react-native-starter.git my-new-app

# Especially important for Ueno employees!
git remote remove origin

# Add your own git repository (optional)
git remote add origin {your own git repository}

# Rename the application
./scripts/rename.sh "My New App" com.ueno.mynewap

# Install dependencies
yarn install

# Install cocoapods
(cd ios; pod install --repo-update; cd -)

# Start developing!
react-native run-ios
```
