
default: install test

install:
	gem install cocoapods --no-ri --no-rdoc
	# gem install xcpretty --xcprettyno-ri --no-rdoc
	pod install

test:
	xcodebuild -workspace EKAlgorithmsApp.xcworkspace/ -scheme EKAlgorithmsSpecs test
	
