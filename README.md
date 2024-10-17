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
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=for-the-badge&logo=apple&logoColor=white)
![MVVM](https://img.shields.io/badge/MVVM-2C2E3E?style=for-the-badge&logo=m&logoColor=white)
![VIPER](https://img.shields.io/badge/VIPER-764ABC?style=for-the-badge&logo=vip&logoColor=white)
![CoreData](https://img.shields.io/badge/CoreData-1572B6?style=for-the-badge&logo=apple&logoColor=white)
![Alamofire](https://img.shields.io/badge/Alamofire-EE4C2C?style=for-the-badge&logo=alamofire&logoColor=white)
![CocoaPods](https://img.shields.io/badge/CocoaPods-E34F26?style=for-the-badge&logo=cocoapods&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)
![SnapKit](https://img.shields.io/badge/SnapKit-33B5E5?style=for-the-badge&logo=snapkit&logoColor=white)
![GCD](https://img.shields.io/badge/GCD-FF4081?style=for-the-badge&logo=gcd&logoColor=white)
![Realm](https://img.shields.io/badge/Realm-39477F?style=for-the-badge&logo=realm&logoColor=white)
![SDWebImage](https://img.shields.io/badge/SDWebImage-0A0A0A?style=for-the-badge&logo=sdwebimage&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Combine](https://img.shields.io/badge/Combine-FF4785?style=for-the-badge&logo=combine&logoColor=white)
![RxSwift](https://img.shields.io/badge/RxSwift-DD0B78?style=for-the-badge&logo=rxswift&logoColor=white)
![XCTest](https://img.shields.io/badge/XCTest-83C9F4?style=for-the-badge&logo=xcode&logoColor=white)
![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=for-the-badge&logo=fastlane&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-00C853?style=for-the-badge&logo=continuous-integration&logoColor=white)



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

