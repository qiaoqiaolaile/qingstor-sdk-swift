# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

target 'QingStorSDK' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  inhibit_all_warnings!

  # Pods for QingStorSDK
  pod 'Alamofire', '~> 4.7'
  pod 'CryptoSwift', '~> 0.9'
  pod 'ObjectMapper', '~> 3.1'

  target 'QingStorSDKTests' do
    inherit! :search_paths
    # Pods for testing
  end
  
  target 'QingStorSDKFeatureTests' do
      inherit! :search_paths
      # Pods for testing
      pod 'Cucumberish'
  end

end
