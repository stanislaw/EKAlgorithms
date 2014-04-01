
travis: install test

install:
	# gem install xcpretty --xcprettyno-ri --no-rdoc
	pod install

test:
	xcodebuild -workspace EKAlgorithmsApp.xcworkspace/ -scheme EKAlgorithmsSpecs test
	
