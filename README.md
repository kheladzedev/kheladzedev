<h1 align = "center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=65&duration=1500&pause=600&color=0EA293background=000000EE&center=true&vCenter=true&multiline=true&width=1920&height=384&lines=Hello+there!;My+name+is+Edward;Welcome+to+my+README" alt="Typing SVG" /></a>
</h1>

[![Telegram](https://img.shields.io/badge/-Telegram-090909?style=for-the-badge&logo=telegram&logoColor=27A0D9)](https://t.me/kheladzedev)
[![Instagram](https://img.shields.io/badge/-Instagram-090909?style=for-the-badge&logo=instagram&logoColor=B4068E)](https://www.instagram.com/kheladzedev)
[![Twitter](https://img.shields.io/badge/-Twitter-090909?style=for-the-badge&logo=Twitter&logoColor=1C9DEB)](https://twitter.com/kheladzedev)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-090909?style=for-the-badge&logo=linkedin&logoColor=007BB6)](https://www.linkedin.com/in/kheladzedev)
[![Vkontakte](https://img.shields.io/badge/-Vkontakte-090909?style=for-the-badge&logo=Vk&logoColor=4F7DB3)](https://vk.com/kheladzedev)
[![Facebook](https://img.shields.io/badge/-Facebook-090909?style=for-the-badge&logo=Facebook&logoColor=1195F5)](https://www.facebook.com/kheladzedev)

```swift
class IOSDeveloper {
    let name: String
    let age: Int
    let languages: [String]
    
    var skills: [String: [String]] = [
        "Principles": ["OOP", "SOLID"],
        "Layout": ["UIKit", "AutoLayout", "SnapKit", "Storyboard"],
        "Dependencies": ["CocoaPods", "Swift Package Manager", "Carthage"],
        "Storage": ["Core Data", "UserDefaults", "FileManager", "Realm"],
        "Networking": ["URLSession", "JSON Parsing", "REST API", "Firebase"],
        "Multithreading": ["GCD", "Dispatch Queues"],
        "Architectural Patterns": ["MVC", "MVVM", "MVVM+C", "MVP", "MVP+C"],
        "Structural Patterns": ["Delegate", "Singleton", "Factory", "Observer", "Facade"],
        "Version Control": ["Git", "GitHub"],
        "Graphics": ["Figma", "Photoshop"],
        "Other Technologies": ["SwiftUI", "MapKit", "Push/Local Notifications", "Multimedia (AVFoundation, Core Audio, AVKit)", "BLE", "iCloud", "Core Animation", "RxSwift", "App Store/TestFlight"],
        "Additional Knowledge": ["Unit Testing", "UI Testing", "Code Review", "Performance Optimization"]
    ]
    
    init(name: String, age: Int, languages: [String]) {
        self.name = name
        self.age = age
        self.languages = languages
    }
    
    func introduce() {
        print("Hi there! I'm \(name), an iOS Developer with \(age) years of experience.")
        print("I specialize in developing iOS apps using Swift and have a strong skillset:")
        
        for (category, skills) in skills {
            print("- \(category): \(skills.joined(separator: ", "))")
        }
        
        print("I'm passionate about creating user-friendly and visually appealing apps.")
        print("Let's work together to build something amazing!")
    }
}

let me = IOSDeveloper(name: "YourName", age: 25, languages: ["Swift"])
me.introduce()
