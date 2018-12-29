# Uncomment the next line to define a global platform for your project
platform :tvos, '12.0'

target 'TVVLCPlayerTest' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for TVVLCPlayerTest
    pod 'TVVLCPlayer', :git => 'https://github.com/kodlian/TVVLCPlayer.git', :tag => '1.1.1'

end

# workaround for https://github.com/CocoaPods/CocoaPods/issues/3289
pre_install do |installer|
  Pod::Installer::Xcode::TargetValidator.send(:define_method, :verify_no_static_framework_transitive_dependencies) {}
end