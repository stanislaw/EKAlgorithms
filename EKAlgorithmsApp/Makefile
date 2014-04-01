
travis: install test

install:
	pwd
	gem install cocoapods --no-ri --no-rdoc --verbose
	# gem install xcpretty --xcprettyno-ri --no-rdoc
	pod install

test:
	xcodebuild -workspace EKAlgorithmsApp.xcworkspace/ -scheme EKAlgorithmsSpecs test
	
