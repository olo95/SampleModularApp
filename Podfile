platform :ios, '11.0'
use_frameworks!
workspace 'SampleModularApp.xcworkspace'
xcodeproj 'ProjectB/ProjectB.xcodeproj'
xcodeproj 'ProjectB/ProjectB.xcodeproj'
xcodeproj 'ProjectA/ProjectA.xcodeproj'

def common
    pod 'RxSwift'
    pod 'RxCocoa'
end

target 'ProjectA' do
    xcodeproj 'SampleModuleA/ProjectA/ProjectA.xcodeproj'
    common
end

target 'ProjectB' do
    xcodeproj 'SampleModuleB/ProjectB/ProjectB.xcodeproj'
    common
end

target 'ProjectC' do
    xcodeproj 'SampleModuleC/ProjectC/ProjectC.xcodeproj'
    common
end
