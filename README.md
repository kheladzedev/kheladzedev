### Hi there 👋
class IOSDeveloper {
    
    let name = "Andrey Rybalkin"
    let age = 26
    let languages = ["Swift", "Obj-C"]
    
    var myStackDictionary: [String: [String]] = [
        
        "Principles":       ["OOP", "SOLID"]
        "Layout":           ["UIKit", "AutoLayout", "SnapKit", "Storyboard"]
        "Dependensies":     ["CocoaPods", "SPM", "Carthage"]
        "Storage":          ["Core Data", "UserDefaults", "FileManager", "Realm"]
        "Networking":       ["URLSession", "JSON Parse", "REST API", "Firebase"]
        "Multithreading":   ["GCD", "DQ's"]
        "Arch. patterns":   ["MVC", "MVVM", "MVVM+C", "MVP", "MVP+C"]
        "Struct. patterns": ["Delegate", "Singleton", "Factory", "Observer", "Facade"]
        "GUI":              ["Git", "GitHub"]
        "Graphics":         ["Figma", "Photoshop"]
    ]
    
    var otherTechnologies: [String] = [
        "SwiftUI",
        "MapKit",
        "Push / Local Notifications",
        "Multimedia (AVFoundation, Core Audio, AVKit)",
        "BLE",
        "iCloud",
        "Core Animation",
        "RXSwift",
        "AppStore / TestFlight"
    ]
    
    func sayHello() {
        print("Thanks for dropping by, hope you find some of my work interesting.")
    }
}
    
let me = IOSDeveloper()
me.sayHello()
