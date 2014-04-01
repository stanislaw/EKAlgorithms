
install:
	gem install cocoapods --no-ri --no-rdoc
	gem install xcpretty  --no-ri --no-rdoc
	pod install

ci:
	export DYLD_FRAMEWORK_PATH=/Applications/Xcode.app/Contents/Developer/Library/Frameworks; xcodebuild -workspace EKAlgorithmsApp.xcworkspace/ -scheme EKAlgorithmsSpecs test
	
