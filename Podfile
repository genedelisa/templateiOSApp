platform :ios, "11.0"
use_frameworks!

project 'templateiOSApp'

def shared_pods
    #pod 'SwiftMusicKit', :path => '/Users/gene/Development/xcode/gene/Swift/Music/SwiftMusicKit'
    
    #pod 'PianoKeyboard', :path => '/Users/gene/Development/xcode/gene/Swift/mypods/PianoKeyboard/PianoKeyboard'

    #pod 'CommonMusicNotation', :path => '/Users/gene/Development/xcode/gene/Swift/mypods/CommonMusicNotation'
    
    # pod 'GDViews', :path => '/Users/gene/Development/xcode/gene/Swift/mypods/GDViews'
    
    pod 'XCGLogger', '~> 6.0.1'
    
    
end

def testing_pods
    pod 'Quick', '~> 1.2.0'
    pod 'Nimble', '~> 7.0.2'
end

target 'templateiOSApp' do
    shared_pods
end

target 'templateiOSAppTests' do
    shared_pods
    testing_pods
end

