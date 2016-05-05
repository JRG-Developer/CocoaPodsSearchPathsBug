platform :ios, '9.0'

target 'CocoaPodsSearchPathsBug' do
  use_frameworks!

  pod 'Alamofire', '~> 3.3'

  target 'CocoaPodsSearchPathsBugTests' do
    inherit! :search_paths  # results in linker error, `Library not loaded`, at runtime

    pod 'EVReflection', '~> 2.28'
  end
end
