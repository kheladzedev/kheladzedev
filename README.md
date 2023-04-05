<div align="center">

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=120&section=header"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=00bfbf&size=40&center=true&vCenter=true&width=1000&lines=Hello!+My+name+is+Edward;Be+Welcome!+:%29)](https://git.io/typing-svg)

<div align="center">

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=120&section=footer"/>

```swift
class IOSDeveloper {

    let name = "Edward Kheladze"
    let age = 27
    let languages = ["Swift", "Obj-C"]
    
    var myStackDictionary: [String: [String]] = [
        "Principles":       ["OOP", "SOLID"],
        "Layout":           ["UIKit", "AutoLayout", "SnapKit", "Storyboard"],
        "Dependensies":     ["CocoaPods", "SPM", "Carthage"],
        "Storage":          ["Core Data", "UserDefaults", "FileManager", "Realm"],
        "Networking":       ["URLSession", "JSON Parse", "REST API", "Firebase"],
        "Multithreading":   ["GCD", "DQ's"],
        "Arch. patterns":   ["MVC", "MVVM", "MVVM+C", "MVP", "MVP+C"],
        "Struct. patterns": ["Delegate", "Singleton", "Factory", "Observer", "Facade"],
        "GUI":              ["Git", "GitHub"],
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
        print("Привет, меня зовут \(name). Я iOS разработчик и являюсь экспертом в использовании следующих технологий: \(languages.joined(separator: ", ")).")
    }
}

// Мой стек технологий
let myStack = IOSDeveloper()
print("\n=== Мой стек технологий ===")
for (category, technologies) in myStack.myStackDictionary {
    print("\n", category, ":")
    for technology in technologies {
        var techColor: String
        switch technology {
        case "Swift", "UIKit", "AutoLayout", "Firebase":
            techColor = "\u{001B}[34m" // синий
        case "Obj-C", "CocoaPods", "Core Data":
            techColor = "\u{001B}[33m" // оранжевый
        default:
            techColor = "\u{001B}[0m" // по умолчанию
        }
        print(techColor + technology)
    }
}

// Информация обо мне и моих навыках
print("\n=== Обо мне ===")
print("\u{001B}[34mИмя:\u{001B}[0m", myStack.name)
print("\u{001B}[34mВозраст:\u{001B}[0m", myStack.age)
print("\u{001B}[34mЯзыки программирования:\u{001B}[0m", myStack.languages.joined(separator: ", "))
print("\u{001B}[34mДругие технологии:\u{001B}[0m")
for technology in myStack.otherTechnologies {
    print("\u{001B}[33m" + technology) // оранжевый
