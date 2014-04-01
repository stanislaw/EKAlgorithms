
travis: install test

install:
	gem install cocoapods --no-ri --no-rdoc --verbose
	gem install xcpretty --xcprettyno-ri --no-rdoc
	pod install --verbose

test:
	xcodebuild -workspace EKAlgorithmsApp.xcworkspace/ -scheme EKAlgorithmsSpecs test
	
