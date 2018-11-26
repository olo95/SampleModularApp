platform :ios, '11.0'
use_frameworks!
workspace 'SampleModularApp.xcworkspace'
xcodeproj 'ProjectB/ProjectB.xcodeproj'
xcodeproj 'ProjectA/ProjectA.xcodeproj'
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/olo95/SamplePodspecRepo.git'

def common
    pod 'RxSwift'
    pod 'RxCocoa'
    pod 'SampleModuleC'
end

target 'ProjectA' do
    xcodeproj 'SampleModuleA/ProjectA/ProjectA.xcodeproj'
    common
end

target 'ProjectB' do
    xcodeproj 'SampleModuleB/ProjectB/ProjectB.xcodeproj'
    common
end
