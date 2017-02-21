# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'OpenSwiftKit' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for OpenSwiftKit
    swift_version = "3.0"
    pod "PromiseKit",               '~> 4.0'
    pod 'AsyncDisplayKit',          '>= 2.0'
    pod 'Alamofire',                '~> 4.3'
    pod 'AlamofireObjectMapper',    '~> 4.0'
    pod 'Kingfisher',               '~> 3.0'
    pod 'RxSwift',                  '~> 3.0'
    pod 'RxCocoa',                  '~> 3.0'
    pod 'SwiftyJSON'
    pod 'RealmSwift'
    pod 'SwifterSwift'
    pod 'TangramKit',               '~> 1.0.3'
    pod 'IGListKit',                '~> 2.0.0'


  target 'OpenSwiftKitTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'OpenSwiftKitUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '3.0'
    end
  end
end

