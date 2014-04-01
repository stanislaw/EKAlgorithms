
install:
	gem install cocoapods --no-ri --no-rdoc --verbose
	gem install xcpretty  --no-ri --no-rdoc --verbose
	pod install --verbose

ci:
	xcodebuild -workspace EKAlgorithmsApp.xcworkspace/ -scheme EKAlgorithmsSpecs test
	
