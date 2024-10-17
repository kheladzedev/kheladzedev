<h1 align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=45&pause=1000&color=0EA293&center=true&vCenter=true&width=1000&lines=Hello+there!;I'm+Edward,+iOS+Developer" alt="Typing SVG" /></a>
</h1>

[![Telegram](https://img.shields.io/badge/-Telegram-090909?style=for-the-badge&logo=telegram&logoColor=27A0D9)](https://t.me/kheladzedev)
[![Instagram](https://img.shields.io/badge/-Instagram-090909?style=for-the-badge&logo=instagram&logoColor=B4068E)](https://www.instagram.com/kheladzedev)
[![Twitter](https://img.shields.io/badge/-Twitter-090909?style=for-the-badge&logo=Twitter&logoColor=1C9DEB)](https://twitter.com/kheladzedev)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-090909?style=for-the-badge&logo=linkedin&logoColor=007BB6)](https://www.linkedin.com/in/kheladzedev)
[![Vkontakte](https://img.shields.io/badge/-Vkontakte-090909?style=for-the-badge&logo=Vk&logoColor=4F7DB3)](https://vk.com/kheladzedev)
[![Facebook](https://img.shields.io/badge/-Facebook-090909?style=for-the-badge&logo=Facebook&logoColor=1195F5)](https://www.facebook.com/kheladzedev)

## 🧑‍💻 About Me
Hi, I'm Edward, an experienced iOS Developer with over 3 years of expertise in building scalable and adaptive applications. I have successfully worked on a wide range of projects, including e-commerce, multimedia streaming apps, and high-performance iOS applications. My core skills include Swift, UIKit, MVVM, VIPER, and performance optimization.

I thrive on tackling complex technical challenges and continuously improving app performance and user experience. I have a deep understanding of iOS architecture and have integrated numerous third-party APIs, ensuring seamless functionality across multiple projects.

- 🔭 Currently working on: **Optimizing multimedia iOS apps for performance**
- 🌱 Currently learning: **SwiftUI, Combine, and ARKit**
- 💬 Ask me about: **iOS development, architecture patterns, performance optimization**

## ⚙️ Technologies & Tools
![Swift](https://img.shields.io/badge/-Swift-090909?style=for-the-badge&logo=swift)
![UIKit](https://img.shields.io/badge/-UIKit-090909?style=for-the-badge&logo=uikit)
![MVVM](https://img.shields.io/badge/-MVVM-090909?style=for-the-badge&logo=mvvm)
![VIPER](https://img.shields.io/badge/-VIPER-090909?style=for-the-badge)
![CoreData](https://img.shields.io/badge/-CoreData-090909?style=for-the-badge&logo=apple)
![Alamofire](https://img.shields.io/badge/-Alamofire-090909?style=for-the-badge&logo=alamofire)
![CocoaPods](https://img.shields.io/badge/-CocoaPods-090909?style=for-the-badge&logo=cocoapods)
![Firebase](https://img.shields.io/badge/-Firebase-090909?style=for-the-badge&logo=firebase)
![SnapKit](https://img.shields.io/badge/-SnapKit-090909?style=for-the-badge&logo=snapkit)
![GCD](https://img.shields.io/badge/-GCD-090909?style=for-the-badge&logo=gcd)

## 📈 GitHub Stats
![Edward's GitHub stats](https://github-readme-stats.vercel.app/api?username=kheladzedev&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kheladzedev&layout=compact&theme=radical)


## 📫 How to reach me
- Telegram: [@kheladzedev](https://t.me/kheladzedev)
- LinkedIn: [kheladzedev](https://www.linkedin.com/in/kheladzedev)

## 🖥️ A bit of code

```swift
class IOSDeveloper {
    let name: String
    let age: Int
    let languages: [String]
    
    var skills: [String: [String]] = [
        "Principles": ["OOP", "SOLID"],
        "Layout": ["UIKit", "AutoLayout", "SnapKit", "Storyboard"],
        "Dependencies": ["CocoaPods", "Swift Package Manager", "Carthage"],
        "Storage": ["Core Data", "UserDefaults", "Realm"],
        "Networking": ["URLSession", "JSON Parsing", "REST API", "Google", "Firebase"],
        "Architectural Patterns": ["MVC", "MVVM", "MVVM+C", "MVP", "MVP+C"],
        "Version Control": ["Git", "GitHub"],
        "Graphics": ["Figma"],
        "Other Technologies": ["SwiftUI", "MapKit", "Push/Local Notifications", "Multimedia (AVFoundation, Core Audio, AVKit)", "App Store/TestFlight"],
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
    }
}

let edward = IOSDeveloper(name: "Edward", age: 27, languages: ["Swift", "Objective-C", "Python"])
edward.introduce()

